# Module 1 Homework: Docker & SQL

## Question 1. Understanding Docker images

Run docker with the python:3.13 image. Use an entrypoint bash to interact with the container.

What's the version of pip in the image?

Origin :: docker pull python:3.13

Run image :: docker run -it --entrypoint bash python:3.13

Check pip version installed :: pip --version

Answer :: pip 25.3 from /usr/local/lib/python3.13/site-packages/pip (python 3.13)

Go to terminal :: exit

## Question 2. Understanding Docker networking and docker-compose

Given the following docker-compose.yaml, what is the hostname and port that pgadmin should use to connect to the postgres database?

```bash
services:
  db:
    container_name: postgres
    image: postgres:17-alpine
    environment:
      POSTGRES_USER: 'postgres'
      POSTGRES_PASSWORD: 'postgres'
      POSTGRES_DB: 'ny_taxi'
    ports:
      - '5433:5432'
    volumes:
      - vol-pgdata:/var/lib/postgresql/data

  pgadmin:
    container_name: pgadmin
    image: dpage/pgadmin4:latest
    environment:
      PGADMIN_DEFAULT_EMAIL: "pgadmin@pgadmin.com"
      PGADMIN_DEFAULT_PASSWORD: "pgadmin"
    ports:
      - "8080:80"
    volumes:
      - vol-pgadmin_data:/var/lib/pgadmin

volumes:
  vol-pgdata:
    name: vol-pgdata
  vol-pgadmin_data:
    name: vol-pgadmin_data

```

To connect `pgadmin`to database `postgres`, we must use the following:

- Hostname :: `db` (Name of the service in YAML file `db:`)

- Port :: `5432` (Port - `5433` in mapping `5433:5432` is for external access used by local PC.)

Answer :: `db:5432`

# Build the environment for PostreSQL with docker

Create folder :: "dados"

Create file docker-compose.yaml

docker compose down

docker compose up -d

Go to folder `dados`

wget https://d37ci6vzurychx.cloudfront.net/trip-data/green_tripdata_2025-11.parquet

wget https://github.com/DataTalksClub/nyc-tlc-data/releases/download/misc/taxi_zone_lookup.csv

mv /mnt/c/Users/jesus/Downloads/taxi_zone_lookup.csv ./data

mv /mnt/c/Users/jesus/Downloads/green_tripdata_2025-11.parquet ./data

# Aceder ao postgrSQL através da imagem do Docker

```bash
docker exec -it [container_id] bash
```

**Conectar ao postgresql**

`psql -U postgres`

`\l`
**Conectar a uma base de dados**

`\c ny_taxi`


```sql
SELECT COUNT(*) FROM yellow_taxi_data WHERE (lpep_pickup_datetime BETWEEN '2025-11-01' AND '2025-12-01') AND trip_distance <= 1;
```

```sql
 SELECT ROUND(SUM(trip_distance)::numeric,2) SUM_TRIP_DISTANCE FROM green_taxi_data WHERE lpep_pickup_datetime::DATE='2025-11-20' AND trip_distance < 100;
```
 sum_trip_distance 
-------------------
           6377.03


ny_taxi=# SELECT ROUND(SUM(GTD.total_amount)::numeric,2) AS TOTAL_AMOUNT_TIPS FROM green_taxi_data GTD LEFT JOIN taxi_zone_lookup TZL ON GTD."PULoca
tionID" = TZL."LocationID" WHERE TZL."Zone" LIKE 'East Harlem North';
 total_amount_tips 
-------------------
         257684.70
(1 row)
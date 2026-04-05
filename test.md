---
title:  (AI-900) Get started with Microsoft Foundry
markmap:
    initialExpandLevel: 1
    maxWidth: 300
---

#  [(AI-900) Get started with Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/)

## Unit 1

### [What is an AI application?](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/2-concepts)

#### Definition
- Artificial Intelligence (AI) refers to systems designed to perform tasks that typically require human intelligence &mdash; such as reasoning, problem-solving, perception, and language understanding.

#### Key AI workloads

- Generative AI
- Agents and automation
- Speech
- Text analysis
- Computer vision
- Information extraction

#### Machine learning

##### Definition

- Enables machines to learn patterns from data and improve performance without explicit programming.

##### Types of ML

###### Supervised and unsupervised learning

- Such as regression (supervised) for predicting prices, classification (supervised) for spam detection and clustering (unsupervised) for customer segmetation.

###### Deep learning

- A specialized branch of ML using neural networks with multiple layers for tasks like image recognition and speech synthesis. Deep learning provides the foundation through neural networks that learn complex patterns from massive datasets.

###### Generative AI

- Uses deep learning capabilities to create new content &mdash; text, images, audio, code &mdash; rather than just classify or predict outcomes.

### AI applications

#### Definition

- An AI application is a software solution that uses AI techniques &mdash; such as computer vision, speech and information extraction &mdash; to perform tasks tha typically require human-like intelligence.

- These applications can understand, reason, learn and respond to inputs in a eay that feels more adaptive and intelligent than traditional software.

#### What are AI applications

##### Model-powered

- Use trained models to process inputs and generate outputs such as text, images ou decisions.

##### Dynamic

- AI apps can improve over time through retaining or fine-tuning.

#### How to interact with AI applications

##### Conversational interfaces

- Users interact via chatbots or voice assistants (such as asking questions, getting recommendations).

##### Embedded features

- AI is integrated into apps for tasks like autocomplete, image recognition or fraud detection.

##### Decision support

- AI applications provide insights or predictions to help users make informed choices (such as personalized shopping, medicar diagnostics).

##### Automation

- AI apps handle repetitive tasks such as document processing or customer service, reducing manual effort.

#### AI apllications in industry

##### Healthcare

- AI- powered diagnostic tools that analyze medical images (such as XRay or MRIs) to help doctors detect deseases more accurately and quickly.

##### Finance

- Fraud detection systems that use AI to monitor transactions in real time and identify suspicious activity, helping prevent financial crimes

##### Retail

- Personalized recommendation engines that analyze customer behaviour and preferences to usggest products, improving the shopping experience.

##### Manufacturing

- Predictive maintenance solutions that use AI to monitor equipment and forecast when machines are likely to fail, reducing downtime and maintenance costs

##### Education

- Intelligent tutopring systems that adapt to each student's learning style and pace, providing customizes feedback and support to enhance learning outcomes.





## Unit 2 

### [Components of an AI application](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/3-components)

#### Data layer 

##### What's in

- Includes the collection, storage and management of data used for training, inference and decision-making.

##### Common datasources

- Structured databases (Azure SQL and PostgreSQL)
- Unstructured data (documents and images)
- Real-time streams

##### Services

- Cosmos DB
- Azure Data Lake

##### What's available

###### Infrastructure-as-a-Service (IaaS)

- IaaS is a cloud computing model that delivers on-demand servers, storage, and networking, allowing businesses to rent resources, scale flexibly, and reduce hardware costs.

- How does IaaS work?
    1. IaaS works by provides virtualized computing resources—such as servers, storage, and networking—online.
    2. Cloud providers host and manage the underlying infrastructure in their data centers, while users access and configure these resources via a web interface or API.
    3. Businesses can scale resources up or down as needed, paying only for what they use.
    4. This eliminates the need for physical hardware management, reduces costs, and makes it possible to rapidly deploy applications and services.

- Benefits of IaaS:
    1. Helps businesses cut costs, scale efficiently, enhance security, and speed up deployment.
    2. Lowers expenses and optimizes costs
        - Removes the expense of setting up and maintaining a physical datacenter, making it a budget-friendly option for cloud migration. 
        - With pay-as-you-go plans, businesses can cut down on hardware and maintenance expenses while allowing their IT teams to focus on core operations.
    3. Boosts IT scale and performance:
        - Makes it easier for businesses to scale globally and accommodate spikes in resource demand.
        - This facilitates faster IT delivery for employees worldwide and improves application performance.
    4. Increases stability and reliability:
        - There's no need for organizations to maintain and upgrade software and hardware or troubleshoot equipment problems.
        - The service provider ensures that the infrastructure is reliable and meets service-level agreements (SLAs).
    5. Improves business continuity:
        - Thanks to their strong infrastructure and security expertise, cloud service providers can often deliver more robust applications and data protection than an individual organization can achieve in-house.
    6. Increases deployment speed:
        - Businesses can set up the infrastructure for new products or initiatives in minutes or hours instead of days or weeks.
        - By eliminating the need to set up and manage physical infrastructure, IaaS helps deliver applications to users faster.

- Common IaaS business scenarios
    1. Lift-and-shift migration:
        - This is the fastest and least expensive method of migrating an application or workload to the cloud.
        - Without refactoring their underlying architecture, organizations can increase the scale and performance, enhance the security, and reduce the costs of running an application or workload.
    2. Test and development:
        - Teams can quickly set up and dismantle test and development environments, bringing new applications to market faster. 
        - IaaS makes it fast and economical to scale dev/test environments up and down.
    3. Storage, backup, and recovery:
        - IaaS eliminates the need for upfront storage investments and data management, which typically requires skilled staff to ensure compliance. 
        - It helps businesses handle unpredictable demand, scale storage as needed, and streamline backup and recovery planning.
    4. Web apps:
        - IaaS provides the necessary infrastructure for web applications, including storage, servers, and networking. 
        - Businesses can quickly deploy web apps and scale resources up or down to accommodate fluctuating demand.
    5. High-performance computing:
        - IaaS supports high-performance computing by providing the power of supercomputers, computer grids, or clusters to solve complex problems. 
        - Applications include protein folding, earthquake simulations, climate modeling, financial forecasting, and product design analysis.
    6. Big data analysis:
        - IaaS enables businesses to process and analyze vast amounts of data efficiently by providing scalable computing power and storage. 
        - This is essential for uncovering insights in areas like customer behavior, market trends, scientific research, and real-time analytics.

- Future trends in infrastructure as a service:
    1. AI-driven automation:
        - IaaS providers are adding more AI and automation to help manage resources, improve performance, and cut down on manual work. 
        - Predictive analytics will help businesses adjust their infrastructure more quickly, while AI as a service (AIaaS) will continue to grow as a cloud service model.
    2. Edge computing growth:
        - As demand increases for faster, real-time applications, IaaS will expand to process data closer to users. 
        - Useful for IoT, live analytics, and 5G-powered applications.
    3. Eco-friendly cloud infrastructure:
        - With a stronger focus on sustainability, IaaS providers are building energy-efficient data centers, working toward carbon-neutral operations, and using AI to make workloads more efficient.

- Key technologies and innovations:
    1. Serverless computing:
        - IaaS providers are offering serverless computing options, allowing businesses to run applications without managing servers. This reduces costs and makes scaling easier.
    2. Graphics processing unit (GPU)-powered computing:
        - High-performance GPUs are becoming more available in cloud environments, helping with AI, deep learning, and complex computing tasks.
    3. Software-defined networking (SDN):
        - SDN allows networks to adjust automatically, improving security, reducing delays, and making infrastructure more efficient.

- FAQ:
    1. What is infrastructure as a service?
        - Infrastructure as a service (IaaS) is a cloud computing model that provides virtualized computing resources online. 
        - Instead of maintaining physical hardware, businesses can rent servers, storage, and networking on a pay-as-you-go basis.
        - This allows for flexible scaling, cost savings, and easier management of IT infrastructure.
    2. What is the difference between SaaS and IaaS?
        - The difference between SaaS and IaaS is that SaaS provides ready-to-use software applications, while IaaS offers cloud-based computing infrastructure. With SaaS, users access applications without worrying about maintenance, whereas IaaS provides the raw computing power needed to run applications, requiring users to manage their own software and configurations.
    3. What is the classification of IaaS?
        - The classification of IaaS falls under cloud computing services, specifically as a foundational layer that provides virtualized hardware resources. IaaS is typically categorized alongside other cloud models such as SaaS (Software as a Service) and PaaS (Platform as a Service), serving as the base infrastructure that supports applications and development environments.
    4. What is an example of an IaaS product?
        - An example of an IaaS product is [Microsoft Azure Virtual Machines](https://azure.microsoft.com/en-us/products/virtual-machines), which provide scalable, on-demand cloud computing resources, allowing businesses to run applications and workloads without maintaining physical servers.
    5. Why use IaaS over PaaS?
        - Using IaaS over PaaS is beneficial for businesses that need more control over their infrastructure and software configurations. While PaaS simplifies development by managing the operating system and runtime environment, IaaS allows organizations to customize their setups, install specific applications, and have greater flexibility in managing their IT resources.

###### Platform-as-a-Service (PaaS)

- Platform services are managed cloud services that provide the foundational building blocks for developing, deploying, and running applications without requiring users to manage the underlying infrastructure.
- It allows developers to focus on writing code, while the cloud provider handles the infrastructure, maintenance, and scalability.
- Includes everything needed for application development, including operating systems, runtime environments, databases, development tools, middleware, and hosting and scaling capabilities.

- How does PaaS work?
    1. Provisioning. 
        - The cloud provider sets up the necessary computing resources, including servers, networking, and storage. They also set up a development environment that includes essential tools, frameworks, and databases.
    2. Application development. 
        - Developers write and test code using built-in development tools, SDKs, and APIs.
    3. Deployment and hosting. 
        - Developers deploy applications directly to the cloud with minimal configuration. The platform handles runtime, middleware, and operating system management.
    4. Scalability and load balancing. 
        - A PaaS automatically scales resources based on demand. Load balancing ensures efficient distribution of traffic to prevent crashes.
    5. Database and storage management. 
        - PaaS provides managed databases with backup and recovery features. It also offers scalable storage solutions for handling application data.
    6. Security and maintenance. 
        - The PaaS provider handles security patches, updates, and infrastructure maintenance. Some platforms also include built-in authentication, authorization, and encryption features.
    7. Monitoring and analytics. 
        - Tools for monitoring app performance, debugging, and logging allow developers to analyze usage patterns and optimize the application.

- Benefits of PaaS
    1. Reduced coding time:
        - PaaS development tools cut the time it takes to code new apps by providing pre-coded application components, such as workflows, directory services, security features, and search.
    2. Increased capabilities:
        - PaaS allows existing teams to focus on building and deploying applications rather than handling infrastructure or maintenance. 
        - PaaS platforms also offer integrated tools for continuous integration and continuous delivery (CI/CD) pipelines, version control, testing, and monitoring. 
        - Developers use these out-of-the-box tools to speed up the development cycle, which minimizes the need for separate teams or additional resources to manage these tasks.
    3. Support for multiple platforms:
        - PaaS supports multiple platforms by providing a unified cloud environment that is used across various types of applications, devices, and operating systems. 
        - This allows businesses and developers to build, deploy, and manage applications that work seamlessly on multiple platforms, such as web, mobile, and desktop, without having to manage different infrastructure for each one.
    4. Access to advanced tools:
        - A pay-as-you-go model makes it possible for individuals or organizations to use advanced development software and business intelligence and analytics tools that might be unavailable or unaffordable otherwise.
    5. Supports distributed teams:
        - Because the development environment is accessed over the Internet, development teams are able to work together on projects, regardless of geographical location.
    6. Manages the full application lifecycle:
        - PaaS provides all the capabilities that you need to support the complete web application lifecycle: building, testing, deploying, managing, and updating within the same integrated environment.

- Common PaaS scenarios:
    1. Development framework:
        - If a team wishes to build a web or mobile application quickly without managing infrastructure, PaaS provides a development framework. 
        - Cloud features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding that developers must do.
    2. Analytics or business intelligence:
        - A PaaS provides a managed environment for data analytics and business intelligence by offering built-in tools for data processing, visualization, and reporting. 
        - Businesses use PaaS to streamline data collection, transformation, and insight generation without managing infrastructure.
    3.  Additional services:
        - PaaS offers a wide range of services to help organizations streamline application deployment, integration, and management. 
        - Key services include: 
            - database management; 
            - API management and integration services; 
            - automation for DevOps; and 
            - security and identity management.

- Future trends in platform as a service
    1. AI and machine learning integration
        - PaaS providers will offer built-in AI and machine learning tools, making it easier to develop intelligent applications without deep expertise in data science.
    2. Security-first PaaS
        - PaaS providers will implement Zero Trust security models, AI-powered threat detection, and compliance automation. 
        - More robust identity and access management (IAM) solutions will enhance data security and prevent cyber threats.
    3. Low-code and no-code development
        - PaaS platforms will provide more low-code and no-code tools, allowing businesses to build applications with minimal programming knowledge. 
        - Citizen developers will use visual development tools to create apps quickly.

- Key technologies and innovations
    1. Serverless PaaS
        - The boundary between PaaS and serverless will blur, offering more event-driven architectures with automatic scaling and cost efficiency. 
        - Developers will focus only on writing functions while the platform handles execution, scaling, and infrastructure.
    2. Multicloud and hybrid cloud PaaS
        - Organizations will adopt multicloud PaaS solutions to avoid vendor lock-in and improve flexibility. 
        - Hybrid PaaS will provide seamless deployment across on-premises and cloud environments, supporting edge computing use cases.
    3. Kubernetes and container-based PaaS
        - PaaS solutions will include Kubernetes for container orchestration, offering better portability, scalability, and microservices support. 
        - Cloud-native development will become the standard, with containerized workloads improving deployment flexibility.

- FAQ:
    1. What is plataform as a service?
        - Platform as a service (PaaS) is a cloud computing model that provides developers with a platform to build, deploy, and manage applications without worrying about the underlying infrastructure. 
        - It allows developers to focus on writing code, while the cloud provider handles the infrastructure, maintenance, and scalability.
    2. Is M365 a PaaS?
        - No, Microsoft 365 is not a PaaS. It is a SaaS solution that provides cloud-based productivity tools like Word, Excel, Outlook, and Teams. 
        - Unlike PaaS, which is designed for application development, Microsoft 365 is a fully managed software suite intended for employees.
    3. Is Azure a PaaS?
        - Microsoft Azure isn’t just a PaaS, it’s a comprehensive cloud platform offering infrastructure as a service (IaaS), PaaS, and Software as a service (SaaS) solutions. 
        - A few examples of Azure PaaS offerings are Azure App Services, Azure Functions, and Azure SQL Database.
    4. Is PaaS better than SaaS?
        - PaaS and SaaS serve different purposes, so neither one is inherently better than the other. 
        - PaaS is ideal for developers who need a platform to build and deploy applications, while SaaS is best for employees who need ready-to-use software without development effort. 
        - The choice depends on the use case—businesses needing custom applications may prefer PaaS, while those wanting fully managed software solutions may benefit from SaaS.
    5. Is PaaS the same as serverless?
        - PaaS and serverless computing are not the same. 
        - PaaS provides a platform with managed infrastructure where applications run continuously. 
        - With the serverless model, developers write and deploy code in the form of functions that execute in response to certain events. With serverless, organizations pay only for the actual compute time used.


###### Software-as-a-Service (SaaS)

- SaaS is a cloud-based software delivery model where individuals or organizations subscribe to applications rather than purchasing and installing them locally. Customers access software over the internet, typically through a web browser, while the cloud service provider manages the underlying infrastructure, security, maintenance, and updates. 
- SaaS is a cloud-based software delivery model where people access applications over the internet, while the cloud service provider handles infrastructure, security, and updates.
- SaaS operates on a subscription basis, eliminating the need for customers to install or maintain software locally.
- SaaS applications are highly scalable, allowing customers to adjust their subscription levels as their needs evolve.
- Multitenant architecture allows a single instance of SaaS software to serve multiple customers, optimizing resources and reducing costs. 
- SaaS advantages include cost efficiency, ease of access, and workforce mobility by providing access to apps and data from any internet-connected device.
- Common SaaS use cases span business management and operations, collaboration and communication, and data analytics and business intelligence. 
- Future SaaS trends include greater AI adoption, the rise of low-code and no-code platforms, and stronger focus on security and compliance.

- How does SaaS work?
    1. SaaS operates on a cloud-based model where software applications are hosted by a service provider and accessed over the internet. 
    2. Instead of purchasing and installing software on local computers or servers, customers subscribe to the software and use it online. 
    3. This approach offers several advantages, including ease of access, scalability, and reduced IT infrastructure needs.
    4. When a customer subscribes to a SaaS application, they typically log in through a web browser. 
    5. The application runs on the service provider's servers, which handle all the processing and data storage. 
    6. This allows customers to access the software from any device with an internet connection, providing flexibility and mobility. 
    7. The service provider manages software maintenance, including updates, security, and backups, so customers always have the latest features and security patches.
    8. From a technical perspective, SaaS providers use multitenant architecture, meaning a single instance of the software serves multiple customers. 
    9. This approach optimizes resources and reduces costs, as infrastructure and maintenance expenses are distributed across many customers. 
    10. SaaS applications are also highly scalable, allowing customers to easily adjust their subscription levels based on their needs, whether that means adding features, increasing storage, or supporting more users.

- Advantages of SaaS:
    1. Access advanced applications
        - SaaS customers can access advanced software without purchasing, installing, updating, or maintaining hardware, middleware, or software. 
        - This makes enterprise applications like enterprise resource planning (ERP) and CRM more affordable to organizations with limited IT resources.
    2. Pay only for what you use
        - Instead of high upfront costs, SaaS customers might have the option to pay only for what they use. 
        - Subscription models automatically scale up or down based on usage needs. 
        - This dynamic scaling prevents overpayment for unused resources during low-demand periods and makes the necessary capacity available during peak times—without manual adjustments or additional investments.
    3. No need for local installation
        - Customers run most SaaS apps directly from their web browser without needing to download and install any software, although some apps require plugins. 
        - This means that customers don’t need to purchase and install special software.
    4. Support for a mobile workforce
        - SaaS supports a mobile workforce by providing access to apps and data from any internet-connected computer or mobile device. 
        - Service providers handle compatibility across devices and manage security, so data is protected without additional in-house expertise.
    5. Access app data from anywhere
        - Storing data in the could empowers SaaS customers to access their information from any internet-connected computer or mobile device. 
        - No data is lost if a user’s computer or device fails.

- Common SaaS scenarios
    1. Business management and operations
        - Cloud-based tools for project management, CRM, accounting, and human resources provide real-time data access to enhance decision-making, streamline workflows, and improve overall efficiently across various departments.
    2. Collaboration and communication
        - SaaS tools like Microsoft Teams support real-time messaging, video conferencing, file sharing, and project management, empowering teams to collaborate seamlessly from any location.
    3. Data analytics and business intelligence 
        - SaaS solutions provide real-time data processing, visualization, and reporting. 
        - They support predictive analytics, trend analysis, and decision-making to help businesses uncover insights, optimize operations, and drive growth. 

- Future trends in SaaS
    1. AI and machine learning
        - Increased adoption of AI and machine learning for more personalized and predictive solutions. 
    2. Low-code and no-code platforms
        - These platforms empower non-technical customers to build custom applications without extensive coding experience.
    3. Enhanced security and compliance
        - Greater emphasis on protecting customer data and meeting regulatory requirements.

- Key technologies and innovations
    1. Vertical SaaS
        - Specific solutions designed for industries like healthcare, finance, and retail.
    2. Micro-SaaS
        - Niche applications that address specialized needs within larger platforms.
    3. API integrations
        - Improved connectivity and seamless interoperability between different SaaS applications.
    4. Mobile-first development
        - Greater focus on mobile-optimized SaaS solutions to support increasing mobile usage.
    5. Evolving pricing models
        - More flexible, value-based pricing structures to better align with customer needs.

- FAQ:
    1. What is SaaS in simple terms?
        - Software as a service (SaaS) is a way of delivering software over the internet. Instead of installing and maintaining software on your computer, you access it online through a subscription with a cloud service provider. 
        - This makes it easy to use, update, and scale according to your needs.
    2. What is an example for SaaS?
        - Azure AI services are an example of SaaS. 
        - These services help developers and organizations quickly build AI-powered applications without requiring them to manage the underlying infrastructure. 
        - They include natural language processing, search, monitoring, translation, speech, vision, and decision-making.
    3. How to identify a SaaS company?
        - A SaaS company provides software on a subscription basis, hosting it in the cloud for customers to access via the internet without installation. 
        - These companies offer scalable solutions, allowing customers to adjust their plans as needed. 
        - They manage automatic updates, ensuring users always have the latest version. 
        - Most SaaS companies use a multitenancy model, where multiple customers share the same infrastructure while maintaining separate data and configurations.
    4. Is SaaS paid monthly?
        - SaaS is often offered on monthly subscription basis. 
        - Some providers also offer annual plans—often at a discounted rate.
    5. Is SaaS a goood to start?
        - Starting a SaaS business might be a strong opportunity. 
        - SaaS offers recurring revenue, scalability, and lower distribution costs. 
        - However, it also requires significant investment in development, marketing, and customer support. 
        - With a strong product idea and a solid execution plan, a SaaS business has the potential to be highly profitable.



###### Model-as-a-service (MaaS)

- Involves hosting pre-trained ML models on cloud infrastructure and making them accessible via APIs.
- This setup allows organizations to take advantage of ML models without having to create and train them from scratch.
- By providing cloud-based access to pre-trained machine learning models and flexible pay-as-you-go pricing, MaaS makes it much easier for businesses of all sizes to build, deploy, and maintain AI solutions, and integrate AI into their applications.
- MaaS provides pre-built models that have been pre-trained on large datasets and are ready for companies to integrate into their AI-powered applications.
- MaaS speeds time to market for AI apps by eliminating time-consuming, resource-intensive model development and management activities.
- By lowering barriers to entry and offering scalable, cost-effective solutions, MaaS represents a pivotal shift in how AI technologies are consumed and integrated into business operations.
- Examples of MaaS use cases include :
    - marketing sentiment analysis, 
    - early fraud detection, 
    - intelligent decision support, 
    - research, and 
    - predictive analytics for proactive healthcare.
- As the MaaS market evolves, it’s likely to foster the development of more sophisticated and specialized models tailored to industry-specific challenges.
- The ongoing evolution and adoption of MaaS will be instrumental in driving AI-powered innovation, efficiencies, and growth across industries moving forward.

- How does MaaS work?
    1. Cloud-based access to ML models, that support a wide range of tasks, such as:
        - Natural language processing
        - Speech recognition
        - Computer vision
        - Anomaly detection
        - Sentiment analysis
        - Recommendation systems
    2. Faster deployment of AI solutions:
        - Eliminates the challenges of developing ML models that requires significant time, resources, and expertise, by providing ready-to-use models that have been pre-trained on large datasets. 
        - Developers integrate these models into their applications via APIs, significantly reducing the time and effort required to deploy AI solutions.

- Benefits of MaaS
    1. Makes AI more accessible
        - MaaS makes AI accessible to businesses of all sizes by allowing them to use sophisticated ML and deep learning models without extensive infrastructure or in-house expertise. 
        - With easy access to pre-trained models, MaaS empowers organizations to quickly integrate AI into their operations. 
        - This approach reduces the barriers to entry, empowering even small businesses to take advantage of AI and ML technologies to drive innovation in their respective fields.
    2. Delivers cost efficiencies
        - MaaS empowers companies to access advanced AI capabilities without the financial burden of building and maintaining their own models. 
        -Building AI models from scratch requires major computational resources and specialized knowledge. 
        - Using pre-built, pre-trained models from cloud providers, organizations achieve significant cost savings on high-performance computing power and dedicated AI teams. 
        - The flexible pay-as-you-go pricing model of MaaS further improves cost efficiencies by allowing businesses to only pay for the AI and ML resources they use.
    3. Provides high-performance scalability
        - MaaS is highly scalable, making it ideal for companies with fluctuating business needs.
        - Its ability to scale up or down based on demand allows business to easily manage varying workloads. 
        - MaaS adjusts to traffic surges or decreases, providing the necessary computational power to maintain optimal performance.
        - Designed to handle large volumes of requests without performance degradation, MaaS helps businesses deliver consistent, reliable AI-driven services to their customers, regardless of the volume of requests. 
        - This helps businesses maintain high levels of service quality and customer satisfaction.

- Common MaaS scenarios
    1. Healthcare: Predictive analytics for patient outcomes
        - By analyzing vast datasets from electronic health records, lab results, and other sources, MaaS forecasts potential health risks, supporting early intervention and personalized care. 
        - This shift to proactive care improves patient outcomes, optimizes resources, and reduces healthcare costs.
    2. Finance: Early detection of fraud and comprehensive risk assessment
        - MaaS empowers financial institutions to analyze transaction data in real time, identifying patterns and anomalies that signal potential fraud. 
        - This proactive approach reduces financial losses and enhances security. 
        - MaaS also supports risk assessments for mitigation strategies and compliance.
    3. Retail: Customer behavior analysis and personalized recommendations
        - With MaaS, retailers analyze data like browsing history and purchase behavior to deliver tailored product suggestions. 
        - This AI-powered approach enhances the shopping experience, boosts customer satisfaction, and drives sales, helping retailers optimize their marketing strategies.

- Future trends in MaaS
    1. Automated machine learning (AutoML)
        - AutoML streamlines the model-building process by automating repetitive tasks, reducing human error, and enhancing model quality and reliability. 
        - This simplification facilitates the creation of more models for MaaS platforms.
    2. Edge computing
        - This decentralized approach reduces latency by bringing data storage and computation closer to data sources, allowing for faster real-time insights and responses. 
        - Additionally, edge computing improves bandwidth efficiency by minimizing data transmission to central data centers.

- FAQ:
    1. What is MaaS?
        - Model as a Service (MaaS) provides pre-trained machine learning models as serverless APIs with flexible pay-as-you-go pricing. 
        - This cloud-based solution removes the need for extensive in-house expertise and infrastructure, allowing developers to quickly and cost-effectively deploy and scale AI applications. 
        - MaaS makes advanced analytics, predictions, and automation accessible to a wider range of organizations, enhancing their ability to innovate and compete.
    2. What are the benefits of MaaS?
        - Model as a Service (MaaS) provides cloud-based access to pre-trained machine learning models with pay-as-you-go pricing, empowering businesses to quickly deploy AI applications without needing extensive in-house expertise and infrastructure. 
        - This approach reduces costs and makes advanced AI capabilities accessible to organizations of all sizes. 
        - MaaS is cost-effective, highly scalable, and significantly lowers barriers to entry for companies seeking to deploy AI-powered solutions.
    3. What is the meaning of «As a Service»?
        - «As a service» is a cloud computing model where customers access services online, paying only for what they use. 
        - This includes Software as a Service (SaaS), Infrastructure as a Service (IaaS), and Platform as a Service (PaaS). 
        - Model as a Service (MaaS) is a newer addition, allowing businesses to quickly deploy AI-powered applications through cloud-based access to pre-trained machine learning models.

###### Artificial Intelligence-as-a-service (AIaaS)

- Artificial intelligence as a service (AIaaS) refers to the provisioning of artificial intelligence (AI) services and tools through a cloud computing platform. 
- AIaaS allows users to access and utilize AI capabilities without the need to invest in and maintain the underlying infrastructure. 
- Businesses and developers can therefore use AI technologies, such as machine learning, deep learning, natural language processing, and computer vision through APIs or other cloud-based services. 
- It provides a more accessible and cost-effective way for organizations to bring AI into their applications and processes.

- How does AIaaS work?
    1. Like infrastructure as a service (IaaS), platform as a service (PaaS), or software as a service (SaaS), AIaaS follows a cloud service model. 
    2. Users interact with AIaaS solutions through APIs, seamlessly integrating AI capabilities into their applications, websites, or services. 
    3. The cloud platforms that host AIaaS provide scalable solutions that allow users to adjust their usage based on application demands and ensure optimal performance.
    4. Additionally, AIaaS may include the management of data processing, such as the storage and processing of large datasets for model training. 
    5. AIaaS providers also often offer pretrained models for tasks like image recognition and language translation, giving users access to sophisticated models without extensive training or expertise.
    6. Users also have the option to customize and train their own models on AIaaS platforms and tailor them to specific business requirements. 
    7. Many AIaaS platforms offer a pay-as-you-go cost structure, which eliminates the need for large upfront investments and makes it a cost-effective solution for incorporating artificial intelligence capabilities into applications.

- Types of AIaaS
    1. Bots
        - Bots, short for robots, are software applications designed to perform automated tasks.
        - In the context of AIaaS, bots often use natural language processing and machine learning to interact with users and provide information or perform actions. 
        - Examples of bots include:
            - customer support chatbots, 
            - virtual assistants, 
            - social media bots, and 
            - other conversational agents.
    2. Machine learning frameworks
        - Machine learning frameworks are tools and libraries that facilitate the development, training, and deployment of machine learning models. 
        - AIaaS provides these frameworks as a service, allowing users to build and deploy models without managing the underlying infrastructure. 
        - Some common use cases for machine learning frameworks include predictive modeling, image recognition, natural language processing, and recommendation systems.
    3. Cognitive computing APIs
        - Cognitive computing APIs provide developers with access to advanced cognitive capabilities such as speech recognition, language understanding, computer vision, and decision making. 
        - Developers use these APIs to easily build applications that perform complex cognitive functions. 
        - Common uses for cognitive computing APIs include language translation, sentiment analysis, image recognition, and voice recognition.
    4. AI-powered data analytics and insights
        - AI-powered data analytics and insights services use machine learning algorithms to analyze large datasets and extract meaningful insights. 
        - These services help organizations make data-driven decisions and discover patterns that may not be apparent through traditional analytics. 
        - Organizations use these services to power predictive analytics, anomaly detection, pattern recognition, recommendation engines, and other data-driven applications.

- Benefits of AIaaS
    1. Cost-effective implementation
        - AIaaS eliminates the need for organizations to invest heavily in building and maintaining their AI infrastructure. 
        - This cost-effective model allows businesses to access advanced AI capabilities without significant upfront expenses.
    2. Access to cutting-edge technology
        - Organizations gain access to the latest AI technologies and advancements provided by AIaaS platforms without the need for in-house expertise. 
        - This opens up access to state-of-the-art models, algorithms, and tools.
    3. Rapid development and deployment
        - AIaaS platforms offer prebuilt models and APIs, which accelerate the development and deployment of AI applications. 
        - This speed is crucial for helping organizations stay competitive and respond quickly to market demands.
    4. Scalability
        - AIaaS providers offer scalable solutions, allowing organizations to adjust resources based on their needs. 
        - This flexibility ensures efficient handling of varying workloads and scalability as businesses grow their AI initiatives.
    5. Stability
        - AIaaS solutions are hosted on cloud infrastructure, they offer consistent reliability and availability, and are updated without disrupting user operations.
    6. Focus on core competencies
        - By outsourcing AI infrastructure management to AIaaS providers, organizations are able to concentrate on their core business activities. 
        - This allows them to focus on strategic initiatives and areas where their expertise lies.
    7. Improved decisionmaking
        - AI-powered analytics and insights services help organizations make informed decisions based on data-driven insights. 
        - This contributes to better strategic planning, resource allocation, and overall decision-making processes.
    8. Enhanced customer experience
        - AI-powered chatbots and virtual assistants improve customer interactions by providing instant and personalized responses. 
        - This leads to enhanced customer satisfaction and engagement, as well as the ability to handle a large volume of inquiries efficiently.
    9. Innovation and experimentation
        - AIaaS gives organizations the opportunity to experiment with and innovate using AI without the need for extensive resources. 
        - This encourages a culture of innovation, allowing businesses to explore new AI-driven applications and services.
    10. Integration with existing systems and applications
        - AIaaS empowers users to integrate AI solutions into their existing systems and applications. With this accessibility, businesses are able to bring powerful AI to their solutions without the need for extensive overhauls.
    11. Reduced time-to-market
        - With pre-built models and APIs, organizations are significantly reducing the time it takes to develop and deploy AI applications. 
        - This agility is crucial in getting products and services to market faster.
    12. Security and compliance
        - AIaaS providers often implement robust security measures to protect user data, ensuring compliance with privacy regulations. 
        - This is be particularly important for organizations operating in industries with stringent data security requirements.

- Best practices for adopting AIaaS
    1. Identifying the right provider
        - To identify the right artificial intelligence as a service provider, organizations should assess their specific needs, considering factors such as the types of AI services offered, scalability, pricing models, security measures, and ease of integration with existing systems. 
        - It's crucial to evaluate provider reputation, customer support, and the compatibility of the offered AI solutions with the organization's goals. 
        - Conducting thorough research, seeking recommendations, and possibly testing trial versions ensures a well-informed decision aligning with the organization's requirements and priorities.
    2. Evaluating data requirements and data quality
        - Organizations evaluating data requirements and quality for AIaaS should first define the specific data needed for their AI applications. 
        - Assessing the volume, variety, and relevance of data is crucial. 
        - Consider the quality of existing data by examining accuracy, completeness, and consistency. 
        - Understand the data sources, ensuring they align with the organization's goals and ethical considerations. 
        - Conducting a thorough data audit and implementing data quality assurance measures will help ensure that the data fed into AIaaS systems is reliable and conducive to effective machine learning model training and performance.
    3. Ensuring regulatory compliance and ethical use of AI
        - Organizations maintain regulatory compliance and ethical use of AIaaS by staying informed about relevant laws and regulations, particularly in data privacy and AI ethics.
        - Implementing robust data governance practices, ensuring transparency in AI decision-making processes, and regularly auditing AI systems for bias and fairness are essential steps. 
        - Establishing clear guidelines and ethical frameworks within the organization, along with promoting responsible AI practices among development teams, will contribute to creating AIaaS programs that align with regulatory standards and ethical considerations. 
        - Regularly reviewing and updating policies in response to evolving regulations and ethical standards is also crucial.
    4. Creating a smooth integration process with existing systems
        - To ensure a smooth integration of AIaaS solutions with existing systems, organizations should conduct a thorough analysis of their current infrastructure, identify potential points of integration, and establish clear communication channels between different components. 
        - Implementing standardized APIs and protocols facilitates seamless data exchange, while comprehensive testing and validation protocols help identify and address compatibility issues early in the integration process. 
        - Regular collaboration between IT teams and AIaaS providers, coupled with a well-defined migration strategy, ensures a cohesive transition and minimizes disruptions, fostering a successful integration of AI capabilities into the existing organizational framework.

- FAQ:
    1. What is AIaaS?
        - Artificial intelligence as a service is a cloud-based model that provides access to AI tools and capabilities on a subscription basis. It allows users to reap the benefits of artificial intelligence without the need for significant upfront investments or specialized expertise, making advanced AI solutions easily accessible and scalable for diverse applications. 
        - AI-as-a-service platforms typically offer a range of pre-built models, APIs, and tools to facilitate integration with existing systems and applications. 
    2. What is an example of AIaaS?
        - One example of how AIaaS might be applied is for customer support services. 
        - Examples include:
            - using natural language processing to analyze customer inquiries, 
            - deploying chatbots for automated assistance, 
            - automating ticket categorization, 
            - utilizing sentiment analysis for understanding customer emotions, 
            - enhancing the knowledge base through automated updates, and 
            - ensuring scalability during peak periods. 
        - Organizations using an AIaaS approach to customer support provide efficient and responsive customer service without having to develop and maintain an extensive, costly AI infrastructure.
    3. Is Azure an AI cloud service provider?
        - Yes, Azure, Microsoft's cloud computing platform, offers a comprehensive set of AI services and tools. 
        - Azure AI includes services for machine learning, natural language processing, computer vision, and speech recognition. 
        - It provides developers with the capabilities to build, deploy, and manage AI solutions in the cloud, making Azure a prominent AI cloud service provider.
    4. What is artificial intelligence?
        - Artificial intelligence (AI) refers to the development of computer systems that perform tasks that typically require human intelligence. 
        - These tasks include learning, reasoning, problem-solving, perception, and language understanding. 
        - AI technologies aim to simulate human cognitive abilities, enabling machines to analyze data, adapt to changing environments, and suggest appropriate actions.

#### Model layer

- The model layer involves the selection, training, and deployment of machine learning or AI models. 
- Models can be pretrained (for example: Azure OpenAI in Foundry Models) or custom-built using platforms like Azure Machine Learning. 
- This layer also includes tools for fine-tuning, evaluating, and versioning models to ensure they meet performance and accuracy requirements. 
- Microsoft Foundry, a unified Azure PaaS for enterprise AI operations, provides a comprehensive model catalog for application developers.

#### Compute layer 

- AI applications require compute resources to train and run models. 
- Microsoft provides several platform options:
    - Azure App Service for hosting web apps and APIs.
    - Azure Functions for serverless, event-driven execution of AI tasks.
    - Containers for scalable and portable deployment of AI models and services. 
        1. Azure Container Instances (ACI) offers lightweight, serverless container execution, perfect for AI workloads needing rapid deployment and simple scaling. 
        2. Azure Kubernetes Service (AKS) is a fully managed Kubernetes service that provides enterprise-level orchestration for AI workloads.

#### Integration & Orchestration layer
- The integration and orchestration layer connects models and data with business logic and user interfaces. 
- Foundry plays a key role here by offering:
    1. An agent Service for building intelligent agents that can reason and act.
    2. AI Tools like speech, vision, and language APIs.
    3. Software Development Kits (SDKs) and APIs for integrating AI capabilities into applications.
    4. Portal tools for managing models, agents, and workflows.

## Unit 3

### [Microsoft Foundry for AI](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/4-microsoft-foundry)

- Microsoft Foundry is a unified, enterprise-grade platform for building, deploying, and managing AI applications and agents. 
- It consolidates models, agent orchestration, monitoring, and governance tools in one platform, offering production-grade infrastructure and security. 
- With Foundry, developers can seamlessly design, customize, and scale generative AI applications using a rich portal experience or integrated SDKs, without worrying about underlying infrastructure complexities.
- Within Foundry's portal, you can work with:
    1. Foundry Models
        - Access to foundation and partner models (Azure OpenAI in Foundry Models, Anthropic, Cohere, etc.).
    2. Agent Service
        - Build and orchestrate multi-step AI workflows.
    3. Foundry Tools
        - Prebuilt Azure services (Vision, Language, Search, Document Intelligence).
    4. Governance & Observability
        - Centralized identity, policy, and monitoring for AI workloads

#### Foundry models

- Foundry supports thousands of models from first-party and diverse third-party providers—including Azure OpenAI in Foundry Models like gpt-4, gpt-5 series, multimodal variants, as well as open-source options such as Meta Llama and Mistral. 
- Enterprise organizations can deploy and manage models directly from Foundry’s model catalog. 
- Foundry offers the ability to test and customize models in a playground setting, deploy models as agents, and manage lifecycle needs, region-specific deployment, and model version control.

#### Agent service

- At the core of Foundry is the Agent Service for building production-ready AI agents that autonomously make decisions, call external tools, and automate workflows. 
- It abstracts orchestration, thread management, tool invocation, and embeds governance such as content safety and observability. 
- Developers can create low-code or code-first multi-agent systems that interact with documents, databases, or other services through various methods and built-in integrations like Azure Functions and Fabric.

#### Foundry tools

- Foundry offers a comprehensive suite of Azure services—such as speech, vision, language, document intelligence, content safety, and embeddings—accessible via portal, APIs, or SDKs. 
- These Foundry Tools provide AI capabilities that can be built into web or mobile applications in a way that’s straightforward to implement. 
- There're over a dozen different services that can be used separately or together to add AI power to applications. 
- Example:
    1. Could use Azure Vision to analyze images, 
    2. Azure Language to summarize text, 
    3. classify information, or extract key phrases, and 
    4. Azure Speech to convert speech to text and text to speech.

#### Governance and Observability
- Governance ensures responsible AI development through compliance, identity management, and risk mitigation.
- Observability delivers end-to-end visibility for performance, safety, and operational efficiency—helping organizations deploy AI confidently and at scale. 
- Foundry embeds governance into the AI development lifecycle to ensure transparency, accountability, compliance, and security at scale. 
- Foundry provides a unified dashboard for metrics on performance, quality, and safety, lifecycle monitoring, and continuous feedback loops.

## Unit 4

### [Get started with Foundry](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/5-foundry-projects)

#### Characteristics of Foundry offerings

1. Prebuilt and ready to use or customize
    - AI has been prohibitive for all but the largest technology companies because of several factors, including the large amounts of data required to train models, the massive amount of computing power needed, and the budget to hire specialist programmers. 
    - Foundry makes AI accessible to businesses of all sizes by using pretrained machine learning models to deliver AI as a service. 
    - Foundry uses high-performance Azure computing to deploy advanced AI models, making decades of research available to developers of all skill levels.
2. Accessed through APIs
    - Foundry models and tools can be built into applications with APIs. 
    - Secure communication with APIs is possible through authentication, the process of verifying that the user or service is who they say they are, and that they're authorized to use the service.
    - Whenever a request is made to use a Foundry resource, that request must be authenticated.
    -  Example:
        - Your subscription and AI service resource is verified to ensure you have sufficient permissions to access it. 
        - This authentication process uses a resource key and an endpoint. 
        - The key is a secret password that the app uses to prove its identity when talking to another service or system.
        - The endpoint describes how to reach the AI service resource instance that you want to use :: `https://cognitiveservices48.cognitiveservices.azure.com/`
        - The resource key protects the privacy of your resource. To ensure your key is always secure, it can be changed periodically.
        - When you write code to access the resource, the keys and endpoint must be included in the authentication header. 
        - The authentication header sends an authorization key to the service to confirm that the application can use the resource.
3. Available on Azure

## Unit 5

### [Understand Azure](https://learn.microsoft.com/en-us/training/modules/get-started-ai-in-foundry/6-about-azure)

- **Microsoft Azure** is a cloud computing platform that provides a wide range of services to help individuals and organizations build, deploy, and manage applications through Microsoft-managed data centers. 
- It offers flexibility, scalability, and global reach, making it a popular choice for businesses of all sizes. 
- Azure supports various programming languages, frameworks, and operating systems, allowing developers to work with the tools they prefer.

#### Cloud capabilities

- Azure delivers core cloud capabilities across four main areas: 
    1. Compute
        - Compute services include virtual machines, containers, and serverless functions that run workloads efficiently.
    2. Storage
        - Storage services offer scalable and secure options for saving data, such as Blob Storage and Azure Files.
    3. Networking
        - Networking services connect resources securely and reliably, using tools like Azure Virtual Network and Load Balancer.
    4. Application services.
        - Application services help developers build and host web apps, APIs, and mobile backends with ease.

#### Understand how Azure organizes your resources

- Azure organizes access and management through a hierarchy of entities
    1. A **tenant** represents a dedicated instance of Azure Active Directory, which handles identity and access management. 
    2. Within a tenant, **subscriptions** define billing boundaries and provide access to Azure services. 
    3. Each subscription can contain multiple **resource groups**, which are logical containers for managing related resources together. 
    4. Resources are the individual services or components—like virtual machines, databases, or storage accounts—that you deploy and manage within Azure.

- Tenants and subscriptions allow for clear separation of concerns across departments or projects.
- Resource groups simplify management by grouping related assets, making it easier to apply policies, monitor usage, and automate deployments. 
- Understanding this hierarchy is essential for efficient cloud governance and cost control in Azure.

#### Foundry runs on Azure

- **Foundry** is an AI development layer within Azure, designed to accelerate building and managing generative AI apps and agents with enterprise-grade governance. 
- **Foundry projects and hubs** are resources that integrate with Azure networking, storage, and security.
- **Foundry Tools and models** are cloud-based and accessed through a Foundry resource. 
    - They are managed in the same way as other Azure services, such as platform as a service (PaaS), infrastructure as a service (IaaS), or a managed database service. 
    - From creating or deleting resources, to availability and billing, the Azure platform and resource manager provides a consistent framework for all your Azure services.

## Unit 6

### Get started with Microsoft Foundry (exercice)

1. Go to [Microsoft Foundry](https://ai.azure.com/).
2. [Nova inscrição](https://azure.microsoft.com/free) dos serviços Azure

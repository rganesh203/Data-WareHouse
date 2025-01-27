# Data-WareHousse
Data Warehouse is a relational database management system (RDBMS) construct to meet the requirement of transaction processing systems. It can be loosely described as any centralized data repository which can be queried for business benefits. It is a database that stores information oriented to satisfy decision-making requests. It is a group of decision support technologies, targets to enabling the knowledge worker (executive, manager, and analyst) to make superior and higher decisions. So, Data Warehousing support architectures and tool for business executives to systematically organize, understand and use their information to make strategic decisions.

Data Warehouse environment contains an extraction, transportation, and loading (ETL) solution, an online analytical processing (OLAP) engine, customer analysis tools, and other applications that handle the process of gathering information and delivering it to business users.

What is a Data Warehouse?
A Data Warehouse (DW) is a relational database that is designed for query and analysis rather than transaction processing. It includes historical data derived from transaction data from single and multiple sources.

A Data Warehouse provides integrated, enterprise-wide, historical data and focuses on providing support for decision-makers for data modeling and analysis.

A Data Warehouse is a group of data specific to the entire organization, not only to a particular group of users.

It is not used for daily operations and transaction processing but used for making decisions.

A Data Warehouse can be viewed as a data system with the following attributes:

It is a database designed for investigative tasks, using data from various applications.
It supports a relatively small number of clients with relatively long interactions.
It includes current and historical data to provide a historical perspective of information.
Its usage is read-intensive.
It contains a few large tables.
"Data Warehouse is a subject-oriented, integrated, and time-variant store of information in support of management's decisions."

Characteristics of Data Warehouse
Data Warehouse
Subject-Oriented
A data warehouse target on the modeling and analysis of data for decision-makers. Therefore, data warehouses typically provide a concise and straightforward view around a particular subject, such as customer, product, or sales, instead of the global organization's ongoing operations. This is done by excluding data that are not useful concerning the subject and including all data needed by the users to understand the subject.

Data Warehouse
Integrated
A data warehouse integrates various heterogeneous data sources like RDBMS, flat files, and online transaction records. It requires performing data cleaning and integration during data warehousing to ensure consistency in naming conventions, attributes types, etc., among different data sources.

Data Warehouse
Time-Variant
Historical information is kept in a data warehouse. For example, one can retrieve files from 3 months, 6 months, 12 months, or even previous data from a data warehouse. These variations with a transactions system, where often only the most current file is kept.

Data Warehouse
Non-Volatile
The data warehouse is a physically separate data storage, which is transformed from the source operational RDBMS. The operational updates of data do not occur in the data warehouse, i.e., update, insert, and delete operations are not performed. It usually requires only two procedures in data accessing: Initial loading of data and access to data. Therefore, the DW does not require transaction processing, recovery, and concurrency capabilities, which allows for substantial speedup of data retrieval. Non-Volatile defines that once entered into the warehouse, and data should not change.

Data Warehouse
History of Data Warehouse
The idea of data warehousing came to the late 1980's when IBM researchers Barry Devlin and Paul Murphy established the "Business Data Warehouse."

In essence, the data warehousing idea was planned to support an architectural model for the flow of information from the operational system to decisional support environments. The concept attempt to address the various problems associated with the flow, mainly the high costs associated with it.

In the absence of data warehousing architecture, a vast amount of space was required to support multiple decision support environments. In large corporations, it was ordinary for various decision support environments to operate independently.

Goals of Data Warehousing
To help reporting as well as analysis
Maintain the organization's historical information
Be the foundation for decision making.
Need for Data Warehouse
Data Warehouse is needed for the following reasons:

History of Data Warehouse
1) Business User: Business users require a data warehouse to view summarized data from the past. Since these people are non-technical, the data may be presented to them in an elementary form.
2) Store historical data: Data Warehouse is required to store the time variable data from the past. This input is made to be used for various purposes.
3) Make strategic decisions: Some strategies may be depending upon the data in the data warehouse. So, data warehouse contributes to making strategic decisions.
4) For data consistency and quality: Bringing the data from different sources at a commonplace, the user can effectively undertake to bring the uniformity and consistency in data.
5) High response time: Data warehouse has to be ready for somewhat unexpected loads and types of queries, which demands a significant degree of flexibility and quick response time.
Benefits of Data Warehouse
Understand business trends and make better forecasting decisions.
Data Warehouses are designed to perform well enormous amounts of data.
The structure of data warehouses is more accessible for end-users to navigate, understand, and query.
Queries that would be complex in many normalized databases could be easier to build and maintain in data warehouses.
Data warehousing is an efficient method to manage demand for lots of information from lots of users.
Data warehousing provide the capabilities to analyze a large amount of historical data.

What are data warehouses used for?
Data warehouses are used in BI, analytics, reporting, data applications, preparing data for machine learning, and data analysis to extract and summarize data from operational databases. Information that is difficult to analyze directly from transactional databases can be analyzed via data warehouses — for example, if management wants to know the total revenues generated by each salesperson on a monthly basis for each product category. Transactional databases may not capture this data, but the data warehouse does.

 

What are the types of data warehouses?
 

Traditional data warehouse: This type of data warehouse stores only structured data. The structure of a data warehouse enables users to quickly and easily access data for reporting and analytics.
Intelligent data warehouse: This is a modern type of data warehouse that is built on a lakehouse architecture and that has an intelligent and automatically optimizing platform. An intelligent data warehouse not only provides access to AI and ML models but also uses AI to assist with queries, dashboard creation, and performance and sizing optimization.
 

Data warehouse architecture
 

A common model for data warehousing architecture is multitiered. This architecture was created by Bill Inmon, the computer scientist often considered the father of the data warehouse.

Bottom tier

The bottom tier of a data warehouse architecture is comprised of data sources and data storage. This tier includes data access methods, like APIs, gateways, ODBC, JDBC and OLE-DB. Data ingestion or ETL is also included in the bottom tier.

Middle tier

The middle tier of a data warehouse architecture is comprised of an OLAP server, which is either relational (ROLAP) or multidimensional (MOLAP). These two types can be combined into a hybrid OLAP (HOLAP).

Top tier

The top tier of a data warehouse architecture is comprised of the front-end clients for querying, BI, dashboarding, reporting and analysis.

discover data warehouse image
What are the three variations of a data warehouse?
Enterprise data warehouse (EDW): A centralized data warehouse that is used by many different teams in an organization. It is often the single source of truth for BI, analytics and reporting.
Operational data store (ODS): A type of data warehouse that focuses on the latest operational or transactional data.
Data mart: A simplified version of the data warehouse that serves a single line of business (LOB) or a single project. A data mart is smaller than an EDW, but the number of data marts typically grows as an organization grows, and LOBs want to self-service.
 

Data lake vs. database vs. data warehouse
 

What is the difference between a data lake and a data warehouse?

Data lakes and data warehouses are two different approaches to managing and storing data.

A data lake is an unstructured or semi-structured data repository that allows for the storage of vast amounts of raw data in its original format. Data lakes are designed to ingest and store all types of data — structured, semi-structured or unstructured — without any predefined schema. Data is often stored in its native format and is not cleansed, transformed or integrated, making it easier to store and access large amounts of data.

A traditional data warehouse, on the other hand, is a structured repository that stores data from various sources in a well-organized manner, with the aim of providing a single source of truth for business intelligence and analytics. Data is cleansed, transformed and integrated into a schema that is optimized for querying and analysis.

An intelligent data warehouse, which uses the lakehouse architecture, also provides a single source of truth for business intelligence and analytics. It extends a traditional data warehouse by storing structured, semi-structured or unstructured data. Data management capabilities like data quality and threshold alerts are included.

What is the difference between a data warehouse and a database?

A database is a collection of structured data, extending beyond text and numbers to images, videos and more. Many refer to this database management system by its acronym: DBMS. A DBMS is the storage system for data that feeds applications and analytics.

A traditional data warehouse, on the other hand, is a structured repository that provides data for business intelligence and analytics. Data is cleansed, transformed and integrated into a schema that is optimized for querying and analysis, including adding common aggregations.
![image](https://github.com/user-attachments/assets/1fd89d06-c846-4bd6-9c53-11e485e3d591)

What is the difference between a data lake, a data warehouse and a data lakehouse?

A data lakehouse is a hybrid approach that combines the best of both worlds. It is a modern data architecture that integrates the capabilities of a traditional data warehouse and a data lake in a unified platform. It allows for the storage of raw data in its original format like a data lake while also providing data processing and analytics capabilities like a data warehouse.

What data warehouse benefits can businesses expect?
 

The consolidation of data obtained from many sources. A data warehouse can become a single point of access for all data, rather than requiring users to connect to dozens or even hundreds of individual data stores.
Historical intelligence. A data warehouse integrates data from many sources to show historical trends.
Separate analytics processing from transactional databases, improving the performance of both systems
Data quality, consistency and accuracy. A well-formed data warehouse uses a standard set of semantics around data, including consistency in naming conventions, codes for various product types, languages, currencies, and so on.
Anyone can discover answers from the data, including users without SQL expertise
 

Challenges with data warehouses
 

No matter the type of data warehouse that you use, challenges remain:

Disjointed tools across data and AI assets create a fragmented approach, which compromises data governance
Users need specialized skills and training to write queries, understand data structures, find and connect to the best data sources, and so on
As data warehouses grow, they slow down — and in the cloud, that gets expensive quickly with cloud compute costs
Scalability and performance

With growing data volumes, a lakehouse architecture distributes computing features, independent of storage, aiming to maintain consistent performance at optimal costs. You need a platform that is designed for elasticity, allowing organizations to scale their data operations as needed. Scalability extends across various dimensions:

Serverless: The platform should enable workloads to adjust and scale elastically based on the required computing capacity. Such dynamic resource allocation guarantees rapid data processing and analysis, even during peak demand.
Concurrency: The platform should leverage serverless compute and AI-driven optimizations to facilitate concurrent data processing and query execution. This ensures that multiple users and teams can undertake analytics tasks concurrently without performance constraints.
Storage: The platform should seamlessly integrate with data lakes, facilitating the cost-effective storage of extensive data volumes while ensuring data availability and reliability. It should also optimize data storage for enhanced performance, reducing storage expenses.
Scalability, though essential, is complemented by performance. The platform should use a variety of AI-driven optimizations to optimize performance:

Optimized query: The platform should use machine learning optimization techniques to accelerate query execution. It leverages automatic indexing, caching and predicate pushdown to ensure queries are processed efficiently, resulting in rapid insights.
Autoscaling: The platform should intelligently scale serverless resources to match your workloads, ensuring that you pay only for the compute you use, all while maintaining optimal query performance.
Fast query performance: The platform should provide extremely fast query performance at low cost — from data ingestion, ETL, streaming, data science and interactive queries — directly on your data lake.
Delta Lake: The platform should use AI models to solve common challenges with data storage so you get faster performance without having to manually manage tables, even as they change over time.
Predictive optimization: This automatically optimizes your data for the best performance and price. It learns from your data usage patterns, builds a plan for the right optimizations to perform and then runs those optimizations on hyper-optimized serverless infrastructure.
Challenges with traditional data warehouses

Traditional data warehouses have an additional set of challenges:

Limited to no support for unstructured data like images, text, IoT data, or messaging frameworks like HL7, JSON and XML. Traditional data warehouses are only capable of storing clean and highly structured data, even though Gartner estimates that up to 80% of an organization’s data is unstructured. Organizations that want to use their unstructured data to unlock the power of AI have to look elsewhere.
No support for AI and machine learning: Data warehouses are purpose-built and optimized for common data warehouse workloads, including historical reporting, BI and querying — they were never designed for or intended to support machine learning workloads.
SQL only: Data warehouses typically offer no support for Python or R, the languages of choice for app developers, data scientists and machine learning engineers.
Duplicated data: Many enterprises have data warehouses and subject-area or (departmental) data marts in addition to a data lake, which results in duplicated data, lots of redundant ETL and no single source of truth.
Tough to keep in sync: Keeping two copies of the data synchronized between the lake and the warehouse adds complexity and fragility that is tough to manage. Data drift can cause inconsistent reporting and faulty analysis.
Closed, proprietary formats increase vendor lock-in: Most enterprise data warehouses use their own proprietary data format rather than formats based on open source and open standards. This increases vendor lock-in, makes it difficult or impossible to analyze your data with other tools and makes it more difficult to migrate your data.
Expensive: Commercial data warehouses charge you for storing your data, and also for analyzing it. Storage and compute costs are therefore still tightly coupled together. Separation of compute and storage with a lakehouse means you can independently scale either as needed.
Separate reporting solutions: Many times you need to ask simple questions of your data without the full features of a separate reporting solution — such as, “What is the sales revenue for Q3?”
Table format lock-in: You need flexibility across lines of business and use cases, but data warehouses sometimes lock you in to a particular table format (for example, Apache Iceberg).
Proprietary table formats

The table format is the primary technology that brings the advantages of data warehouses to data lakes. Table formats organize data and metadata in a way that represents the state of a table over time.

Proprietary table formats are typically used in cloud environments, where efficient access to large datasets is crucial for tasks like analytics, reporting and machine learning. Specific vendors will create file formats or structures to address specific issues, such as reducing storage size, reducing read/writer speeds or adding version control.

Databricks’ proprietary format, Delta Lake, is an open source, open format data management and governance layer that combines the best of both data lakes and data warehouses. Some of the key features include:

ACID transactions: Delta Lake enables consistent data even while running concurrent operations like updates, deletes and insertions. This ensures your data is always up to date and consistent.
Scalable metadata: As datasets grow, Delta Lake scales with it and allows users to store metadata in tables. This results in data changes that are easier to track and share.
Schema enforcement: Delta Lake ensures that all of your data adheres to a specific format in a table.
Compatibility with Apache Spark™: Since Delta Lake is open source, it is compatible with Apache Spark APIs. You can use Delta Lake in your existing Spark applications without modifying your code.
To avoid open table format (OTF) lock-in, or having to choose between Delta Lake and Apache Iceberg, you can use a universal format like Delta Lake UniForm.

Multicloud

Your organization may have data spread across two or more cloud providers to optimize costs or to fit the particular needs of your dataset. This can create problems if data is managed on different networks and with different schema for storing data.

A modern lakehouse architecture can manage data across multiple cloud service providers instead of being tied to a single cloud system. This allows your organization to:

Distribute data: With data across different cloud platforms, your business can find the collection of services that best work with your budget or compliance concerns.
Enhance resilience: Multicloud environments improve data availability by spreading workloads and backups across several providers. This can be crucial if any one cloud service experiences an outage or unexpected downtime.
Data integration: A data warehouse that supports multicloud can also integrate data from across these sources in real time, giving you access to quality data and better decisions.
Compliance: Multicloud architecture can help you meet specific legal and regulatory requirements that may dictate where your data is stored geographically, or how it is stored across multiple cloud services.
Challenges with intelligent data warehouses

Intelligent data warehouses have a different set of challenges:

This modern approach is still evolving, so you need an organization willing to evolve their strategy
AI policies: Your organization should set policies governing which people and systems should be able to use the AI features in an intelligent data warehouse
 

What solutions does Databricks have for data warehousing?
 

Databricks provides an intelligent data warehouse, Databricks SQL, which is built on the open data lakehouse architecture. Databricks SQL is part of an integrated platform, the Data Intelligence Platform, that includes ML, data governance, workflows and more. By using an open, unified foundation for all your data, you get ML/AI, streaming, orchestration, ETL and real-time analytics, data warehousing, unified security, governance and cataloging, as well as unified data storage for reliability and sharing in the same platform. In addition, because the Databricks Data Intelligence Platform is built on an open data lakehouse architecture, you can store all raw data like logs, texts, audio, video and images.

discover data warehouse marketecture
To build a successful lakehouse, organizations have turned to Delta Lake, an open source, open format data management and governance layer that combines the best of both data lakes and data warehouses. The Databricks Data Intelligence Platform uses Delta Lake to give you:

World-record data warehouse performance at data lake economics
Serverless SQL compute that eliminates the need for infrastructure management
Seamless integration with the modern data stack, like dbt, Tableau, Power BI and Fivetran to ingest, query and transform data in place
A first-class SQL development experience for every data practitioner across your organization with ANSI-SQL support
Fine-grained governance with data lineage, table/row-level tags, role-based access controls and more
AI-powered data intelligence engine to understand the semantics of your data

In summary, the main difference between a data lake, a traditional data warehouse and a data lakehouse is their approach to managing and storing data. A traditional data warehouse stores structured data in a predefined schema, a data lake stores raw data in its original format, and a data lakehouse is a hybrid approach that combines the capabilities of both.

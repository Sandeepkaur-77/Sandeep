# What is Datawarehouse
A data warehouse is a type of data management system that is designed to enable and support business intelligence (BI) activities, especially analytics. 
Data warehousing is the process of constructing and using a data warehouse. A data warehouse is constructed by integrating data from multiple heterogeneous sources that support analytical reporting, structured and decision making.
Data Warehouse environment contains an extraction, transportation, and loading (ETL) solution, an online analytical processing (OLAP) engine, customer analysis tools, and other applications that handle the process of gathering information and delivering it to business users.

# History of Datawarehouse
The Datawarehouse benefits users to understand and enhance their organization’s performance. The need to warehouse data evolved as computer systems became more complex and needed to handle increasing amounts of Information. However, Data Warehousing is a not a new thing.

- Here are some key events in evolution of Data Warehouse

1960- Dartmouth and General Mills in a joint research project, develop the terms dimensions and facts.

1970- A Nielsen and IRI introduces dimensional data marts for retail sales.

1983- Tera Data Corporation introduces a database management system which is specifically designed for decision support

Data warehousing started in the late 1980s when IBM worker Paul Murphy and Barry Devlin developed the Business Data Warehouse.

However, the real concept was given by Inmon Bill. He was considered as a father of data warehouse. He had written about a variety of topics for building, usage, and maintenance of the warehouse & the Corporate Information Factory.

# A Data Warehouse can be viewed as a data system with the following attributes:
1.	It is a database designed for investigative tasks, using data from various applications.
2.	It supports a relatively small number of clients with relatively long interactions.
3.	It includes current and historical data to provide a historical perspective of information.
4.	It contains a few large tables.

# Data warehouse architecture

Generally speaking, data warehouses have a three-tier architecture, which consists of a:

- Bottom tier: The bottom tier consists of a data warehouse server, usually a relational database system, which collects, cleanses, and transforms data from multiple data sources through a process known as Extract, Transform, and Load (ETL) or a process known as Extract, Load, and Transform (ELT).
- Middle tier: The middle tier consists of an OLAP (i.e. online analytical processing) server which enables fast query speeds. Three types of OLAP models can be used in this tier, which are known as ROLAP, MOLAP and HOLAP. The type of OLAP model used is dependent on the type of database system that exists.
- Top tier: The top tier is represented by some kind of front-end user interface or reporting tool, which enables end users to conduct ad-hoc data analysis on their business data.

# Types of data warehouses

- Cloud data warehouse
 
A cloud data warehouse is a data warehouse specifically built to run in the cloud, and it is offered to customers as a managed service. Cloud-based data warehouses have grown more popular over the last five to seven years as more companies use cloud services and seek to reduce their on-premises data center footprint.

With a cloud data warehouse, the physical data warehouse infrastructure is managed by the cloud company, meaning that the customer doesn’t have to make an upfront investment in hardware or software and doesn’t have to manage or maintain the data warehouse solution.

- Data warehouse software (on-premises/license)
 
A business can purchase a data warehouse license and then deploy a data warehouse on their own on-premises infrastructure. Although this is typically more expensive than a cloud data warehouse service, it might be a better choice for government entities, financial institutions, or other organizations that want more control over their data or need to comply with strict security or data privacy standards or regulations.

- Data warehouse appliance
 
A data warehouse appliance is a pre-integrated bundle of hardware and software—CPUs, storage, operating system, and data warehouse software—that a business can connect to its network and start using as-is. A data warehouse appliance sits somewhere between cloud and on-premises implementations in terms of upfront cost, speed of deployment, ease of scalability, and management control.

# Characteristics of Data Warehouse
                                 
"Data Warehouse is a subject-oriented.integrated time-variant and non-volatile store of information in support of management's decisions."

- Subject-Oriented

A data warehouse target on the modeling and analysis of data for decision-makers. Therefore, data warehouses typically provide a concise and straightforward view around a particular subject, such as customer, product, or sales, instead of the global organization's ongoing operations. This is done by excluding data that are not useful concerning the subject and including all data needed by the users to understand the subject.

- Integrated

A data warehouse integrates various heterogeneous data sources like RDBMS, flat files, and online transaction records. It requires performing data cleaning and integration during data warehousing to ensure consistency in naming conventions, attributes types, etc., among different data sources.

- Time-Variant

Historical information is kept in a data warehouse. For example, one can retrieve files from 3 months, 6 months, 12 months, or even previous data from a data warehouse. These variations with a transactions system, where often only the most current file is kept.

- Non-Volatile

The data warehouse is a physically separate data storage, which is transformed from the source operational RDBMS. The operational updates of data do not occur in the data warehouse, i.e., update, insert, and delete operations are not performed. It usually requires only two procedures in data accessing: Initial loading of data and access to data. Therefore, the DW does not require transaction processing, recovery, and concurrency capabilities, which allows for substantial speedup of data retrieval. Non-Volatile defines that once entered into the warehouse, and data should not change.

# Goals of Data Warehousing
1. To help reporting as well as analysis
2. Maintain the organization's historical information.
3. Be the foundation for decision making.

# Benefits of Data Warehouse
1.	Understand business trends and make better forecasting decisions.
2.	Data Warehouses are designed to perform well enormous amounts of data.
3.	The structure of data warehouses is more accessible for end-users to navigate, understand, and query.
4.	Queries that would be complex in many normalized databases could be easier to build and maintain in data warehouses.
5.	Data warehousing is an efficient method to manage demand for lots of information from lots of users.
6.	Data warehousing provide the capabilities to analyze a large amount of historical data.

# Need for Data Warehouse
Data Warehouse is needed for the following reasons:
1. Business User: Business users require a data warehouse to view summarized data from the past. Since these people are non-technical, the data may be presented to them in an elementary form.
2. Store historical data: Data Warehouse is required to store the time variable data from the past. This input is made to be used for various purposes.
3. Make strategic decisions: Some strategies may be depending upon the data in the data warehouse. So, data warehouse contributes to making strategic decisions.
4. For data consistency and quality: Bringing the data from different sources at a commonplace, the user can effectively undertake to bring the uniformity and consistency in data.
5. High response time: Data warehouse has to be ready for somewhat unexpected loads and types of queries, which demands a significant degree of flexibility and quick response time.
6. 
# What Is a Data Warehouse Used For?

Here, are most common sectors where Data warehouse is used:

1. Airline:
In the Airline system, it is used for operation purpose like crew assignment, analyses of route profitability, frequent flyer program promotions, etc.

2. Banking:
It is widely used in the banking sector to manage the resources available on desk effectively. Few banks also used for the market research, performance analysis of the product and operations.

3. Healthcare:
Healthcare sector also used Data warehouse to strategize and predict outcomes, generate patient’s treatment reports, share data with tie-in insurance companies, medical aid services, etc.

4. Public sector:
In the public sector, data warehouse is used for intelligence gathering. It helps government agencies to maintain and analyze tax records, health policy records, for every individual.



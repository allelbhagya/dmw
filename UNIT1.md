Q1

![Data-warehouse-architecture](https://github.com/allelbhagya/dmw/assets/80905783/c4d35035-48b9-4900-b6e7-f78164e1232e)

A data warehouse is a centralized repository that stores data from various sources and facilitates the retrieval and analysis of that data to support business intelligence and decision-making processes. The architecture of a data warehouse typically consists of several components that work together to ensure data is collected, transformed, stored, and made available for analysis. Here are the key components of a typical data warehouse architecture:

1. **Source Systems:**
    - *Operational Databases:* These are the systems where day-to-day transactional data is generated and stored, such as sales transactions, customer interactions, etc.
    - *External Data Sources:* Data may also come from external sources, such as third-party data providers, industry databases, or public sources.
2. **Data Extraction:**
    - *ETL (Extract, Transform, Load) Processes:* ETL processes are responsible for extracting data from source systems, transforming it into a format suitable for analysis, and loading it into the data warehouse. This ensures that data in the warehouse is consistent and conforms to a common structure.
3. **Staging Area:**
    - *Staging Database:* Extracted data is often first loaded into a staging area or a staging database. This serves as an intermediate storage where data can be cleansed and transformed before being loaded into the data warehouse.
4. **Data Warehouse Database:**
    - *Data Warehouse Database:* This is the core component where the transformed and cleansed data is stored. It is specifically designed for efficient querying and reporting, often using a multidimensional model (like star or snowflake schema).
5. **Data Mart:**
    - *Data Marts:* Data marts are subsets of the data warehouse that are focused on specific business lines, departments, or subject areas. They are designed to serve the needs of a particular group of users.
6. **Metadata Repository:**
    - *Metadata:* Metadata includes information about the data, such as its source, meaning, relationships, and transformation processes. A metadata repository is crucial for managing and documenting the data warehouse environment.
7. **OLAP (Online Analytical Processing):**
    - *OLAP Cube:* OLAP cubes are multidimensional structures that facilitate fast and complex queries against the data warehouse. They allow users to analyze data from different dimensions and hierarchies.
8. **Data Access Tools:**
    - *Query and Reporting Tools:* These tools allow end-users to interact with the data warehouse, run queries, and generate reports.
    - *Data Visualization Tools:* Tools for creating charts, graphs, and dashboards to present data in a visually understandable format.
    
    Q2
    
1. Multiple data types
2. Data Visualization
3. parallel processing
4. query tools
5. browser tools
6. data fusion
7. agent technology
8. syndicated data
9. multidimensional analysis
10. data warehouse and ERP
11. active data warehousing
12. data warehousig and CRM
    
    Q3
    
    A **Data Mart** is a subset of a directorial information store, generally oriented to a specific purpose or primary data subject which may be distributed to provide business needs. Data Marts are analytical record stores designed to focus on particular business functions for a specific community within an organization. Data marts are derived from subsets of data in a data warehouse, though in the bottom-up data warehouse design methodology, the data warehouse is created from the union of organizational data marts.
    
    The fundamental use of a data mart is **Business Intelligence (BI)** applications. **BI** is used to gather, store, access, and analyze record. It can be used by smaller businesses to utilize the data they have accumulated since it is less expensive than implementing a data warehouse.
    

    
    # Reasons for creating a data mart
    
    - Creates collective data by a group of users
    - Easy access to frequently needed data
    - Ease of creation
    - Improves end-user response time
    - Lower cost than implementing a complete data warehouses
    - Potential clients are more clearly defined than in a comprehensive data warehouse
    - It contains only essential business data and is less cluttered.
    
    # Types of Data Marts
    
    There are mainly two approaches to designing data marts. These approaches are
    
    - Dependent Data Marts
    - Independent Data Marts
    
    difference between data warehouse and data mart
    
    | Data Warehouse | Data Mart |
    | --- | --- |
    | Data warehouse is a Centralised system. | While it is a decentralised system. |
    | In data warehouse, lightly denormalization takes place. | While in Data mart, highly denormalization takes place. |
    | Data warehouse is top-down model. | While it is a bottom-up model. |
    | To built a warehouse is difficult. | While to build a mart is easy. |
    | In data warehouse, Fact constellation schema is used. | While in this, Star schema and snowflake schema are used. |
    | Data Warehouse is flexible. | While it is not flexible. |
    | Data Warehouse is the data-oriented in nature. | While it is the project-oriented in nature. |
    | Data Ware house has long life. | While data-mart has short life than warehouse. |
    | In Data Warehouse, Data are contained in detail form. | While in this, data are contained in summarized form. |
    | Data Warehouse is vast in size. | While data mart is smaller than warehouse. |
    | The Data Warehouse might be somewhere between 100 GB and 1 TB+ in size. | The Size of Data Mart is less than 100 GB. |
    | The time it takes to implement a data warehouse might range from months to years. | The Data Mart deployment procedure is time-limited to a few months. |
    | It uses a lot of data and has comprehensive operational data. | Operational data are not present in Data Mart. |
    | It collects data from various data sources. | It generally stores data from a data warehouse. |
    | Long time for processing the data because of large data. | Less time for processing the data because of handling only a small amount of data. |
    | Complicated design process of creating schemas and views. | Easy design process of creating schemas and views. |

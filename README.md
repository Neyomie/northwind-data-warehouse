# Data Storage Solutions for Data Analytics
As part of our group project developing a dimensional data warehouse for sales analysis with the Northwind dataset, my primary contributions focused on the ETL processes using SSIS and the creation of visualizations and reports in Tableau and SSRS. These elements were critical in transforming raw data into actionable business insights. This repo holds files and folders I used. The project structure is shown below.

│   Data Storage for Data Analytics Report.docx
│   Data_Storage_Presentation.pptx
│   Individual Contribution Report.docx
│   NorthwindSalesPerformance.twbx
│
├───Database
│       northwind.sql
│
├───Neo4j
│   │   Neo4j code.csv
│   │
│   ├───data to import
│   │       customers.csv
│   │       employees.csv
│   │       products.csv
│   │       sales.csv
│   │       time.csv
│   │
│   └───Neo4j screenshots
│           Q1.jpeg
│           Q2.jpeg
│           Q3.jpeg
│           Q4.jpeg
│           Q5.jpeg
│           Q7.jpeg
│
├───northwind datatset csv files
│       categories.csv
│       customers.csv
│       employee-territories.csv
│       employees.csv
│       order-details.csv
│       orders.csv
│       products.csv
│       regions.csv
│       shippers.csv
│       suppliers.csv
│       territories.csv
│
├───SSIS
│   └───Northwind Sales ETL
│       │   Northwind Sales ETL.slnx
│       │
│       ├───.vs
│       │   ├───Northwind Sales ETL
│       │   │   └───CopilotIndices
│       │   │       └───18.4.111.64248
│       │   │               CodeChunks.db
│       │   │               SemanticSymbols.db
│       │   │
│       │   └───Northwind Sales ETL.slnx
│       │       ├───copilot-chat
│       │       │   └───6d82ff37
│       │       │       └───sessions
│       │       │               8ffb3d98-3a26-4d01-bc03-9333c07a7e81
│       │       │
│       │       ├───FileContentIndex
│       │       └───v18
│       │               .suo
│       │               DocumentLayout.backup.json
│       │               DocumentLayout.json
│       │
│       └───Northwind Sales ETL
│           │   Load_Dimensions.dtsx
│           │   Load_Sales_Fact.dtsx
│           │   Load_Staging.dtsx
│           │   Master ETL.dtsx
│           │   MFENA.NorthwindDW.conmgr
│           │   Northwind Sales ETL.database
│           │   Northwind Sales ETL.dtproj
│           │   Northwind Sales ETL.dtproj.user
│           │   NorthwindFull.dtsx
│           │   Project.params
│           │
│           ├───bin
│           │   └───Development
│           │           Northwind Sales ETL.ispac
│           │
│           └───obj
│               └───Development
│                       BuildLog.xml
│                       DimCustomer.dtsx
│                       Load Categories.dtsx
│                       Load Customers.dtsx
│                       Load DimCustomer.dtsx
│                       Load DimEmployee.dtsx
│                       Load Dimensions.dtsx
│                       Load DimProduct.dtsx
│                       Load DimTime.dtsx
│                       Load Employees.dtsx
│                       Load OrderDetails.dtsx
│                       Load Orders.dtsx
│                       Load Products.dtsx
│                       Load Sales Fact.dtsx
│                       Load_Custmers.dtsx
│                       Load_Customers.dtsx
│                       Load_Dimensions.dtsx
│                       Load_Sales_Fact.dtsx
│                       Load_Staging.dtsx
│                       Master ETL.dtsx
│                       MFENA.NorthwindDW.conmgr
│                       Northwind Sales ETL.dtproj
│                       Project.params
│
└───SSRS
        Report.pdf
        SalesReport.rdl

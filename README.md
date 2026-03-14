# DataWareHouse_DataModel_FirstPrinciples
Fundamentals of Data Warehousing and Data modelling <br>
<b>Introduction</b>
Modern organizations run multiple operational systems such as:<br>
- E-commerce platforms
- ERP systems
- CRM systems

These systems store transactional data required for daily operations. However, running heavy analytical queries on operational systems can:<br>
- Slow down production systems
- Affect business operations
- Cause performance bottlenecks

To solve this, organizations build a Data Warehouse.<br>
A Data Warehouse collects data from operational systems, restructures it, and provides a platform optimized for analytics and reporting.<br>
The pipeline typically follows: <br>
Source Systems > ETL > Staging > Transformation > Core Layer <br>
The Core Layer contains Fact Tables and Dimension Tables, designed using Data Modeling.<br>

<b>Architecture Overview</b>

The complete architecture follows these stages:

Operational Database (OLTP) sales(database)-- [Extract] ->Staging Layer --[Transformation] --> Core Data Warehouse Layer --[Dimension Tables & Fact Tables] --> Analytics / BI Tools / Data Scientists

![Data Warehouse Flowchart](Datawarehouse&modelling%20Flowchart.png)

# Extract Transform Load - Project 2
![ETL](/Images/ETL_img.jpg)


#### What is ETL?
<p>We are living in a world of data. The volume of data that is being generated and collected continues to increase at an exponential rate.
As the amount of data grows, the importance of making use of that data grows as well. This data is immensely valuable for analytics, data science, and machine learning, not only to present valuable information and noticeable trends but also to derive business insights and predictions.
The data that is being captured and stored cannot be used in its raw form. Processing the raw, messy data into clean, consistent and reliable data is a critical step before it can be used.</p>

ETL, which stands for Extract, Transform, and Load, is the process to
* Extract data from various sources 
* Transform the data into a clean, usable format
* Load the data into target database systems that end-users can access and use for further analysis, to make business decisions and, to solve problems.

### How ETL works
<p>Lets understand each step of the ETL process</p>

#### Extract
Raw data is extracted from various data sources, which can be structured or non structured. These sources can include but are not limited to:

* APIs, JSON, CSV, XML files
* RDBMS(MS SQl Server, MySql etc.) or NoSQL servers (MongoDB etc.)
* CRM (Salesforce Sales Cloud, Quickbase etc.) and ERP systems(Katana, Oracle NetSuite etc)
* Web pages

#### Transform
The second step consists of transforming the raw data that has been extracted from the above-mentioned sources into a format that can be used by different applications.
This can be like a staging area where the data gets cleansed, mapped, and transformed, often to a specific schema, so it meets operational requirements. 

This phase can involve the following tasks:

* Filtering, handling null values, removing duplicates, validating, and normalizing the data.

* Creating primary and foreign key relationships, applying referential integrity if using relational databases, and redistributing clean data into the right tables.

* Formatting the data into tables or joined tables to match the schema of the target data systems.

* Performing calculations or summarizations on the raw data. This can include changing row and column headers for consistency, converting dates,  or other units of measurement, editing text strings, etc.

* Conducting tests/audits to ensure data quality and compliance.

* Encrypting, or protecting data governed by industry standards or government regulations.

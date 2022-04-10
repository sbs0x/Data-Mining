# Data Mining
- The process of extracting valid , previously unknown, comprehensible and actionable information from large database and using it to make crucial business decisions is known as data mining.
- Data mining is concerned with analysis of data and use of software technique for finding hidden and unexpected patterns and relationship in sets of data.
- It is the process of discovering meaningful patterns and trends often previously unknow, by shifting large amount of data, using pattern recognition, statistical and mathematical techinques.
- It refers to "extracting" or "mining" knowledge from large amount of data stored in database as data warehouse , or other information repositories.
- The main goal of this technique is to find patters that were previously unknown. once these patterns are found, they can further be used to make certain decisions for development of their business.

Three steps are involved. They are:
1. Exploration: Data are cleaned and tranfore into another form.
2. Pattern identification: ONce data is explored, refined, then the second step is pattern identification. Identify and choose patterns which makes best predictions.
3. Deployment: Patterns are now deployed for desired outputs.

### Functions of Data mining 
In general data mining tasks can be classified into 2 categries;

- Descriptive Mining tasks characterize the general properties of data in the database
-  Predictive mining tasks perform conclusion on the current data in order to make predicton.

### The Data mining functionalities are as follows:
1. Concept / Class Description:
 - Data mining can be used to describe individual classes and concepts.
 - These descriptions can be derived via data characterization or data discrimation.

2. Association:
 - Association is one of the best known data mining technique.
 - In association, a pattern is discovered based on the relationship between items in same transcation . That's why, association technique is also known as relation technique.
 - This technique is used in market basket analysis.

3. Prediction:
 - It is one of the data mining technique that discover relationship between independent variables and relationship between dependent and independet variables.

4. Classification:
 - It is a classic data mining technique based on machine learning.
 - Classification makes use of mathematical techniques such as decision tree, linear programming neural network and statistics.
 - In classification, we develop a software that can learn how to classify data items into groups.

5. Clustering 
 - It is the method of grouping objects in such a way that objects with similar features come together and object with disimilar features go apart.
 - It is a unsupervised data mining and it is not a single specific algorithm but a general method to solve the task.
 eg: K-means clustering and hierarchical clustering are common clustering algorithms used in data mining.
 
6. Outlier Analysis:
 - A database may contain data objects that don't satisfy with general behavior or model of data. These data are outliers.
 - Most data mining methods discards outliers as noise or exceptions. However, in some applications such fraud detection, the rare events can be more interesting than the more regularly occuring ones.

### Major issues in Data Mining
1. Mining Methodology & user interaction issues
2. Performance issues
3. Issues Relating to the Diversity of database types




## Architecture of Data mining 
The major components of data mining system are:
1. Database, Data warehouse , WWW or other information repository
 - This is one or a set of databases, data wareshouse, spread sheets or other kinds of information repositories.
 - Data cleaning and data integration techinques may be performed on the data.

2. Database or Datawarehouse server
 - the database or data warehouse server is responsible for fetching the relevent data, based on the user's data mining requests.

3. Knowledge Base:
 - This is the domain knowledge that is used to guide the search or evaluate the interestingness of resulting patterns.
 - It is simply stored in the form of set of rules.

4. Data mining Engine:
 - this is essential to data mining system & consists of sets of functional modules for tasks such as characterization classification, prediction, association and corelation analysis, cluster analysis, evaluation anlysis & so on.

5. Pattern Evaluation Module:
 - It may use interestingness thresholds to filter out discovered patterns.

6. User Interface
 - This module communicates between users snd data mining system, allowing the user to interact with the system by specifying a data mining query or  tasks

### Application of Data mining
- Market Analysis and management 
- Risk analysis & management
- Fraud detection and management
- Sports
- Space Science
- Internet Web surf-Aid
- Social web & Networks
- Research Analysis
- Education



## Data Warehouse
- The term "Data Warehouse" was first coined by Bill Inmon in 1990. According to Inmon, a data warehouse is a subject -oriented, integrated , time variant and non-volatile collection of data.
- A data ware house is a repository of information collected from multiple siurces, stored under a unified schema & that usually resides at a single site.
- Data warehouse is a database, which is kept separate from organizational operational database
- There is no frequent updating done in data warehouse.
- It also contains historical data, which helps the organization to analyze its business.


# Features / Characteristics of Data Warehouse
1. Subject-oriented 
2. Integrated 
3. Time variant
4. Non-volatile

1. Subject-Oriented 
- A data warehouse is a subject oriented because it provides information around a subject rather than organizations ongoing activites.

2. Integrated:
- Data warehouse is constructed by integrating data from hetergenous sources such as relational databses , flat files etc.

3. Time Variant 
- Historical data is kept in a data warehouse. for eg: one can retrive data from 3 months, 12 months or even older data from a data warehouse.

4. Non-Volatile
- Once data in the data warehouse, it will not change. previous data is't reased when new data is added to it.
- The data warehouse doesn't require any transcation processing, recovery and concurrency controls , because it is physically stored and separated from operational databse.

# Functions of Data Warehousing
- As already mentioned, data warehousing is a method for gathering and controlling data from different sources making the data easily avaliable for querying and analysis.

1. Data extraction: Involves gathering data from multiple hetergenous sources
2. Data cleaning: Involves finding and correcting the error in the data
3. Data transformation: Involves converting the data from legacy format to warehouse format.
4. Data loading: Involves sorting, summarizing, consolidating,checking integrity and building indices and partitions.
5. Refereshing : Involves updating from data sources to warehouse. 

# Issues in Data Warehousing
- Building a data warehouse is very difficuilt and a pain. It is challenging.
- Some of the major issues involved in building data ware house are:
i. General Issues
ii. Technical Issues
iii. Cultural Issues

# Application Of Data warehousing
1. Information Processing:
 - A data warehouse allows to process the data stored in it. The data can be processed by means of quering, basic statistical analysis, tables, charts or graphs.

2. Analytical Processing:
 - A data warehouse supports analytical processing of the information stored in it. The data can be analyzed by means of basic OLAP operation including slide and dice, drill-down, drill up and pivoting.

3. Financial Services
4. Banking 
5. Banking Services
6. Consumer goods 
7. Retail Sectors


# KDD (Knowledge Discovering from Data)
- Many People treat data mining as a synonym for another popularly used term, Knowledge Discovery from Data (KDD)
- Alternatively, others view data mining as simply an essential step in the process of knowledge discovery 
- Knowledge discovery consists of an iterative sequence of the following steps:
1. Data cleaning
2. Data Integarion
3. Data selection 
4. Data transformation
5. Data Mining
6. Patterns Evaluation 
7. Knowledge Presentaion


1. Data cleaning
- It removes noise and inconsistent data.
- It removes errors from data

2. Data Integration
- This combines data from various multiple data sources.

3. Data Selection
- Data relevent to the analysis task are retrieved from the database.

4. Data transformation
- Data are transformed or consolidated into forms appropriate fro mining by performing summary or aggregation operations.

5. Data Mining
- An essential process where intelligent methods are applied in order to axtract data patterns.

6. Patterns Evaluation 
- Identifies the truely interesting patterns representing knowledge based on some interestingness measures.

7. Knowledge Presentation
- It is the presentation of knowledge to users for visualization in terms of tree, table, chart etc.
- knowledge representation techniques are used to present the mined knowledge to the user. eg: Histogram



# DBMS vs Data Warehouse

<table>
  <tr>
    <th>S.N</th>
    <th>DMBS</th>
    <th>Data Warehouse</th>
  </tr>
  
  <tr>
    <td>1</td>
    <td>It uses online transcation processing (OLTP)</td>
    <td>It uses Analytical processing(OLAP)</td>
   <tr>
      
  <tr>
    <td>2</td>
    <td>A organized collection of related data stores in a tabular format</td>
    <td>It is a repository of information from multiple database.</td>
  </tr>
  
   <tr>
    <td>3</td>
    <td>It is Application oriented</td>
    <td>It is Subject oriented</td>
  </tr>
  
   <tr>
    <td>4</td>
    <td>It manages current data</td>
    <td>It manages large amount of historical data</td>
  </tr>
  
   <tr>
    <td>5</td>
    <td>Constructing a DBMS isn't so expensive.</td>
    <td>Constructing a DBMS Can be expensive.</td>
  </tr>
  
   <tr>
    <td>6</td>
    <td>ER modeling technique is used for RBMD database design</td>
    <td>Data modeling technique is used for data warehouse design.</td>
  </tr>
   <tr>
    <td>7</td>
    <td>Optimized for write operations.</td>
    <td>Optimized for read operations.</td>
  </tr>
   <tr>
    <td>8</td>
    <td>The database Size is from 100MB to 100GB</td>
    <td>Database size is from 100GB to 100TB</td>
  </tr>
   <tr>
    <td>9</td>
    <td>The No of users is in thousands</td>
    <td>The no of users is in hundreds.</td>
  </tr>
   <tr>
    <td>10</td>
    <td>It focuses on data in</td>
    <td>It focues on information out</td>
  </tr> <tr>
    <td>11</td>
    <td>It provides detailed data </td>
    <td>it provides Summerized data</td>
  </tr>
   <tr>
    <td>12</td>
    <td>OLTP system are used by clearks , DBA. </td>
    <td> OLAP system is used by managers , executives and analysts.</td>
  </tr>
   <tr>
    <td>13</td>
    <td>The no of records access in tens. </td>
    <td>The no of records access in millioons.</td>
  </tr>
   <tr>
    <td>14</td>
    <td>DBMS supports concurrency control and recovery mechanisms. </td>
    <td>Data warehouse don't support concurrency control and recovery mechanisms.</td>
  </tr>
   <tr>
    <td>15</td>
    <td>DBMS is designed for well known tasks and workloads such as hasing and indexing using Primary keys. </td>
    <td>Data warehouse is designed for complex queries and present a general form of data.</td>
  </tr>
      
  </table>



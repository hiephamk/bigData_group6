#### bigData_group6
#### Source of Dataset: https://www.kaggle.com/datasets/mexwell/california-google-local-data
#### Tools: Python, PySpark, PyMongo, Pandas, Matplotlib
#### summary:
  The dataset includes two json files. The first file, name “meta-California.json” contains 16 columns, and 515,961 rows. The second file, name “review-California_10.json” contains 9 columns and 44,476,890 rows.
This is a group work for Big Data Project
**Main goal:**
- Demontrate end-to-end Big Data pipeline, 
- showcasing data processing, analysis
- and optimization techniques using Apache Spark and MongoDB.

**Database:** California Google Local Data - 13GB, JSON format
(Source: https://www.kaggle.com/datasets/mexwell/california-google-local-data)
<img width="716" alt="image" src="https://github.com/user-attachments/assets/0fd91bdd-e7ea-421a-9e43-33fe40f32ad1" />

About architecture of the solution (Spark + MongoDB pipeline), spark serves as primary proccessing engine to load the dataset from json source into a DataFrame,
perform reproccessing tasks and execute analytical operations such as aggregations. 
The proccessed data is then seamlessly transferred to MongoDB. Spark writes proccessed DataFrame to MongoDB collections and 
MongoDB supports adhoc queries and retrieval back into Spark for interative analysis. 

****Implementation (notebook attached)** **

- Step-by-step execution of the project 

- Spark transformations and queries performed 

- MongoDB integration and query performance tuning 

**Results & Insights **
Questions need to be answered: 

 Imagine we own the database from Google. Based on the types of customers, we can provide many services. 

- When visiting California, which companies/services we would like to recommend to our customers (in case a travel agency wants to know which is the most attractive destination)
- If customers want to improve company service/product, which factors cusotmers should look into?  For example Choose a specific company which has average rating 3.6 and read the review which is rating 1 & 2
- Using sentiment analysis: extract information from the text, for example the words ‘bad’ or ‘stay away’

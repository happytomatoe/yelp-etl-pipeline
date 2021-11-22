#   Instructions



Udacity Provided Project
In the Udacity provided project, you'll work with four datasets to complete the project. The main dataset will include data on immigration to the United States, and supplementary datasets will include data on airport codes, U.S. city demographics, and temperature data. You're also welcome to enrich the project with additional data if you'd like to set your project apart.

To help guide your project, we've broken it down into a series of steps. Detailed steps are included in the project instructions page.
## Step 1: Scope the Project and Gather Data
Since the scope of the project will be highly dependent on the data, these two things happen simultaneously. In this step, you’ll:

Identify and gather the data you'll be using for your project (at least two sources and more than 1 million rows). See Project Resources for ideas of what data you can use.
Explain what end use cases you'd like to prepare the data for (e.g., analytics table, app back-end, source-of-truth database, etc.)

## Step 2: Explore and Assess the Data
Explore the data to identify data quality issues, like missing values, duplicate data, etc.
Document steps necessary to clean the data
## Step 3: Define the Data Model
Map out the conceptual data model and explain why you chose that model
List the steps necessary to pipeline the data into the chosen data model
## Step 4: Run ETL to Model the Data
Create the data pipelines and the data model
Include a data dictionary
Run data quality checks to ensure the pipeline ran as expected
Integrity constraints on the relational database (e.g., unique key, data type, etc.)
Unit tests for the scripts to ensure they are doing the right thing
Source/count checks to ensure completeness
## Step 5: Complete Project Write Up
What's the goal? What queries will you want to run? How would Spark or Airflow be incorporated? Why did you choose the model you chose?
Clearly state the rationale for the choice of tools and technologies for the project.
Document the steps of the process.
Propose how often the data should be updated and why.
Post your write-up and final data model in a GitHub repo.
Include a description of how you would approach the problem differently under the following scenarios:
- If the data was increased by 100x.
- If the pipelines were run on a daily basis by 7am.
- If the database needed to be accessed by 100+ people.

# Project ideas
Criteria: has form of fact and dimensions tables
1) MovieLens dataset - https://www.kaggle.com/rounakbanik/the-movies-dataset
2) https://www.kaggle.com/yelp-dataset/yelp-dataset?select=yelp_academic_dataset_business.json
3) https://www.kaggle.com/yekahaaagayeham/ads-data-jobathon-june21-analytics-vidhya
4) Airline data - https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009
5) 
# Yelp:
1) Download dataset - https://www.kaggle.com/yelp-dataset/yelp-dataset

TODO: 
- https://stackoverflow.com/questions/38825836/write-spark-dataframe-to-postgres-database
# nosql-challenge

## Database Setup and Database analysis Jupyter Notebook

### Background
-----------------------------------------------------------------------------------
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

### Overview
-----------------------------------------------------------------------------------
This Python program is designed to setup a Mongo database from a json resource, and provide analysis on said database.
### Main Function
-----------------------------------------------------------------------------------
### Database setup

We will use Mongoimport to convert the json file into a database and collection. We will use Pymongo to clean the data by changing three fields from string data types into the proper Integer or Double data type. We will also use pymongo to update the database with a new restaurant. The database and collection will be assigned to variables to prepare for analysis. 

### Database Analysis

Once we have the database setup, we will use pymongo to create queries on the documents in the database collection. Some of the queries will use the aggregation pipeline method. These queries will be assigned to variables, where we will use Pandas to convert them into dataframes.

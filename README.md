# Assignment-9
## Part A: MongoDB Compass Tasks
Database & Collection Setup:
Created a new database called netflixDB and a collection named titles. 
Imported the netflix_cleaned.csv file using MongoDB Compass.

Visual Queries (Filters):

Retrieved all TV Shows released after 2018.

Fetched content produced in India.

Filtered shows under the Drama genre.

Update Operation:
Replaced all "country": "Unknown" values with "Not Specified".

Delete Operation:
Deleted all documents where the year_added was less than 2010.

## Part B: Python + MongoDB (PyMongo)
Database Connection & Data Insertion:
Established a connection to MongoDB using PyMongo and inserted the dataset into the titles collection.

Querying via Python:

Printed the first 5 documents.

Displayed all Movies from the United States.

Identified the Top 5 most common ratings in the dataset.

Update & Delete Operations:

Updated all records with "rating": "TV-MA" to "Mature".

Deleted all records where release_year is less than 2000.

Aggregation Pipeline:
Used an aggregation query to display the Top 3 countries with the highest number of content entries.

This project demonstrates my ability to work with NoSQL databases both visually and programmatically—using MongoDB Compass for GUI-based operations and PyMongo for automation, data querying, updating, deletion, and aggregation pipelines.

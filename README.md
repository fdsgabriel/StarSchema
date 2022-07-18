# StarSchema

The main role of this repo is transform a raw data sample structure to star schema structure

For that I used PostgreSQL, SQL and Shell

The sample data can be found at Postgres site or in this repo. As you can see there are many tables and its schema it is not 
well organized.

Kick off: the star schema (SS) must to have enought information about any movie, customer, store and time (date). To do so, the
SS is going to be like the final schema diagram with 4 dimension tables (dimDate, Store, Movie and Customer) and 1 fact table (factSales).

Steps: 
  - Load the data into Postgres;
  - Create tables;
  - Insert data into these tables;
  - Create fact table.
  
SSs are very important now a days because when we have a great amount of data a good SS could easy computer process, reduce time query and be more readable as well.

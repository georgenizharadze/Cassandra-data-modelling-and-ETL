# Cassandra-data-modelling-and-ETL

This is an education project to grasp the funadamentals of NoSQL databases, namely, partition row store database Cassandra. The exercise involves data modeling, building of an ETL pipeline and implementation of the relevant data definition and query statements in CQL (Cassandra Query Language). 

The project is based on a hypothetical case of a music streaming app start-up, which currently keeps all the logs of its clients' sessions in daily csv files. Hence, the objective of the project is to migrate the data into appropriately designed tables in Cassandra and enable required analytic queries.  

## Database design considerations

In Cassandra, data modeling is led by the understanding of the types of queries one expects to be performing on the database. Denormalization and redundancy are inherent to Cassandra databases, for the benefit of query efficiencies on big data volumes. Moreover, any attributes included in the WHERE statements have to be part of the table's primary key. 


## Requirements

- Cassandra database server
- Python 3 version
- Python `cassandra` database API
- Python `os, glob, csv and pandas` packages
- Jupyter Notebook 


## Running the code

The instructions at to the types and sequence of code to run, together with the relevant code, are included in the Jupyter Notebook.
# Data Modeling with Cassandra

## introduction
Sparkify is a startup with a music streaming app. Data scientists at Sparkify are particularly interested in understanding what songs users are listening to.

The goal of this project is to define a data model that will help our data scientists answer questions about user activity. In this case, we are working with a NoSQL database, Apache Cassandra, which means we have to be especially intentional in our data modeling. We first need to understand what queries our data scientists would like to run, and then we can design tables to fit those queries. We will be aiming for "1 query, 1 table".


## Build ETL Pipeline
Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
Test by running SELECT statements after running the queries on your database

### Subset of our data after the ETL pipeline:


![Blankdiagram](image_event_datafile_new.jpg)

## Library:
- import pandas as pd
- import cassandra
- import re #Regular expression 
- import os # operating system
- import glob
- import numpy as np
- import json
- import csv






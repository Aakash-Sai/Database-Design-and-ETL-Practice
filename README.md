## Overview
To practice Database Design and ETL, I decided to reverse-engineer an existing SQLite database by utilizing metadata SQL queries to extract crucial details about tables and attributes. The goal was to identify the database's logical structure and subsequently replicate it in my PostgreSQL database schema. Through careful examination of the source database's structure, columns, constraints, and relationships, I implemented a set of tables on the PostgreSQL server. To aid in the process, I crafted an Entity-Relationship Diagram. Following this, I established connections to both source and destination databases, extracted data from source tables, transformed values as needed, and loaded the processed data into the destination tables. Managing sizable tables posed a challenge, requiring me to process them in chunks to avoid memory issues during extraction and loading. Python helped a lot in that aspect. Finally, I validated the data and ran some analytical queries to fetch data. Despite encountering various challenges, the experience was a significant learning opportunity and I look forward to learning more. 

Data Source: Chicago Crimes Data (https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data)

## Tools Used
* Python
* SQL (PostgreSQL, SQlite)
* Jupyter Notebook
* Draw.io (for ERD)


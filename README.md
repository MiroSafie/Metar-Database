# Metar-Database
Metar Database is a database wich tracks weather for flight and other aerial operations.

## Overview
This project was created to learn new skills and showcase them.
The coding languages used were **Python** & **MySQL**.
* **Python**: ETL, Web Scraping, Categorising the data and Creating a Python to MySQL Database connection
* **MySQL**: Creating a Schema, Tables and Views

## How the project works
1. Python script Web Scrabes for metar data.
2. The raw data is upload to the database with a python script using mysql.connector.
3. After that the data gets categorised with a python script.
   * Location, Timestamp, Wind, Wind Variability ect Also categories created for the analysis purpose: Rain and Major Weather wich are booleans
4. The categorized data is then upload to the database using mysql.connector python script.

## Future for the project
- [ ] This project will be used to learn analysis.
- [ ] This project will be used to learn to showcase analysis with PowerBi.

# big-data-engineering-with-python-2024
Big Data Engineering with Python 2024 Course
# Overview
This project is designed to fetch financial data from the Settrade API and store it in either PostgreSQL and Cassandra. Additionally, it includes functions for stock data management, such as creating tables, fetching candlestick data, and plotting stock price charts.


# Installation

Before using this project, install the required Python libraries:
![Uploading Screenshot 2025-03-18 193824.png…]()


# API Configuration

Create a .csv file in the project directory.

Add API credentials:
![alt text](<Screenshot 2025-03-18 194126.png>)

# Database Setup

# PostgreSQL

Install PostgreSQL and create a database named technical_Data.

Update the database connection settings in the script:
![alt text](<Screenshot 2025-03-18 194158.png>)

# Cassandra

Install Apache Cassandra and create a keyspace settrade_api.

Connect to Cassandra in the script:
![alt text](<Screenshot 2025-03-18 193913.png>)
![alt text](<Screenshot 2025-03-18 193926.png>)

# Database Structure

PostgreSQL: stock_financials
![alt text](<Screenshot 2025-03-18 054943.png>)
![alt text](<Screenshot 2025-03-18 055000.png>)
![alt text](<Screenshot 2025-03-18 055019.png>)
![alt text](<Screenshot 2025-03-18 055049.png>)

# Cassandra: candlestick_data
![alt text](<Screenshot 2025-03-18 193926-1.png>)

# Sample Code

Fetching Candlestick Data
![alt text](<Screenshot 2025-03-18 1938481.png>)

# Plotting Stock Data
![alt text](<Screenshot 2025-03-18 194041.png>)
![alt text](<Screenshot 2025-03-18 200212.png>)

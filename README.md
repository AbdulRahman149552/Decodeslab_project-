Decodelabs Project 3: SQL Data Analysis

Project Overview

This project is part of the Decodelabs Industrial Training Kit and focuses on using SQL to analyze an e-commerce order dataset.

The analysis was completed using PostgreSQL and covers data loading, validation, filtering, aggregation, grouping, date analysis, customer analysis, percentage analysis, and business-focused questions.

Dataset

Source: Dataset for Data Analytics.xlsx

Records: 1,200

Columns: 14

Database: PostgreSQL

Main table: orders

Main columns

Column

Description

order_id

Unique order identifier

order_date

Date the order was placed

customer_id

Customer identifier

product

Product purchased

shipping_address

Shipping address

payment_method

Payment method used

order_status

Current order status

tracking_number

Shipment tracking number

coupon_code

Coupon used, where available

referral_source

Source through which the customer arrived

total_price

Total value of the order

quantity

Number of units purchased

unit_price

Price per unit

items_in_cart

Number of items in the cart

Objectives

The main objectives of this project were to:

Load the dataset into PostgreSQL.

Validate the imported data.

Practice fundamental SQL queries.

Calculate business metrics such as revenue and average order value.

Analyze products, customers, payment methods, referral sources, and order statuses.

Answer practical business questions using SQL.

SQL Concepts Used

The project demonstrates the use of:

CREATE TABLE

INSERT INTO

SELECT

WHERE

ORDER BY

GROUP BY

HAVING

COUNT()

SUM()

AVG()

ROUND()

EXTRACT()

Subqueries

CASE

Percentage calculations

Top-N analysis

Date-based analysis

Analysis Sections

The SQL script is organized into the following sections:

Create Table

Load Data

Data Validation

SELECT

WHERE

ORDER BY

Basic Aggregations

GROUP BY

HAVING

Date Analysis

Customer Analysis

Top 10 Analysis

Percentage Analysis

CASE Analysis

Business Questions

Executive Summary Query

Business Questions

The project uses SQL to answer questions such as:

Which product generates the most revenue?

Which payment method is used most often?

Which referral source generates the most revenue?

Which order status has the highest number of orders?

What is the overall average order value?

How are orders and revenue distributed across products and other categories?

PostgreSQL Setup

1. Create a database

Open PostgreSQL using pgAdmin and create a database, for example:

CREATE DATABASE decodelabs_project3;

Connect to the database before running the project script.

2. Run the SQL file

Open:

dat analysis project 3L.sql

in the pgAdmin Query Tool and execute the script.

The script creates the orders table, loads the dataset through SQL INSERT statements, validates the data, and runs the analysis queries.

Project Files

Project_3_SQL_Data_Analysis/
│
├── dat analysis project 3.sql
└── README.md

Tools

PostgreSQL

pgAdmin

SQL

Author

AbdulRahman Akorede Oladokun

Data Analysts & Data Scientists 

This project demonstrates my practical use of SQL to move from raw order data to structured analysis and business-focused insights. 

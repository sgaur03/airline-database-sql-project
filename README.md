✈️ SQL Capstone Project – Airline DB
📌 Overview

This project is a SQL-based capstone focusing on querying an airline database to answer a variety of business questions. It covers real-world SQL skills such as:

Data formatting

Table joins

Window functions (RANK, ROW_NUMBER)

Aggregations (SUM, COUNT, MIN, MAX)

Filtering and grouping

Date & time functions

The dataset and practice environment are available in Skillovilla’s Airline DB Playground:
Airline DB Playground

📂 Project Structure

The project contains 30 SQL problems ranging from basic to advanced difficulty.
Each problem includes:

Question – Business requirement

Expected Output – Column names and output format

SQL Query – Solution

🛠 Skills Demonstrated

SELECT Queries – Retrieving specific columns and formatting output

JOINs – Combining data from multiple tables (JOIN, INNER JOIN)

Aggregations – COUNT(), SUM(), MIN(), MAX()

Grouping & Filtering – GROUP BY, HAVING

Date & Time Functions – TO_CHAR(), EXTRACT()

Window Functions – RANK(), ROW_NUMBER() for ranking and ordering results

Conditional Filtering – WHERE, IN, BETWEEN, LIKE

Business Case Queries – Highest paying passengers, cancelled flights refunds, longest flights, etc.

📋 Example Problem

Question:
Represent the book_date column in yyyy-mmm-dd format using the Bookings table.

Expected Output:

book_ref | book_date   | total_amount


Solution:

SELECT 
    book_ref, 
    TO_CHAR(book_date, 'yyyy-mmm-dd') AS book_date, 
    total_amount
FROM bookings;

🗂 Topics Covered in Queries

Data formatting with TO_CHAR()

Joining passenger, flight, and booking tables

Finding least/most frequent seat allocations

Monthly highest/lowest paying passengers

Identifying nonstop vs. multi-flight journeys

Flights without boarding passes

Longest flight durations

Morning flights & earliest departures per airport

Airports with most/least departures

Cancelled and delayed flights by aircraft type

Passenger refunds due to cancellations

Range-based aircraft filtering

Seat counts per fare category

First/last flights per airport & date

Flight counts for specific routes and airports

🚀 How to Use

Visit the Skillovilla Airline DB Playground.

Run each query to verify the results match the Expected Output.

Modify queries to explore other data insights.

📜 License

This project is for educational purposes. Queries and logic are free to use and adapt.

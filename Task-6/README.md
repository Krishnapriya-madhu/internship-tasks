Imported the provided online sales CSV dataset into the MySQL table using LOAD DATA LOCAL INFILE.
Verified the imported data and checked the total number of records.
Used SQL aggregation functions:
SUM() to calculate monthly revenue.
COUNT(DISTINCT order_id) to calculate monthly order volume.
Extracted year and month from order dates using YEAR() and MONTH() functions.
Grouped sales data by year and month using GROUP BY.
Sorted the results chronologically using ORDER BY.
Generated a final analysis table showing monthly revenue trends and order volume, helping identify sales patterns over time

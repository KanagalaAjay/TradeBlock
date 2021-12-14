# TradeBlock

Objective: Write a program to collect book information from http://books.toscrape.com/
1. Scrape product description and all product info for all books in the Science and Poetry categories, and...
2. Save results to a MYSQL database ( Dump20211214.sql file) and csv file (books_data.csv)

Mostly builtin libraries were used. You may have to install mysql-connector library to connect to MySQL (pip install mysql-connector-python)

The program is located in Extract_book_details.ipynb in jupyter notebook format.
This file is reading secrets from secrets.txt file to read connections for MYSQL server (password and other details has been changed in this file)

The file is running succesfully in the system, It created dump file(attach is the dump file and xml file from the output)
The file can be run directly in the jupyter notebook format. Except for the MYSQL connection as I could not set up remote connection due to time restrictions.







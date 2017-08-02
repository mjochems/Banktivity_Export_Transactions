# Banktivity Export Transactions

## Background
[Banktivity 6](http://https://www.iggsoftware.com/banktivity/), an excellent Personal Finance App for macOS, stores data in a standard SQLite database saved on your Mac. This Python script uses SQL to query the database and extract data.

## Requirements
* Banktivity 6 data file (.bank6)
* Python 3.5+

## Python Script
Script has read only access to your database.
* Returns all transaction data (including Security Trades).
* Exports results to a CSV (comma seperated) text file saved to User desktop.
* CSV file can be opened in Excel or Text Editor for further analysis and review of your data. 

## Data file Location
Please edit Python Script **line 14** to point to the specific Finder path of your Banktivity 6 data file



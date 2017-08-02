# Banktivity Transactions Export

## Background
Banktivity 6 for macOS uses a standard SQLite database saved on your Mac. Python script uses SQL to query this database and return data.

## Python Script
Script has Read Only access to your database.
* Returns all transaction data (including Security Trades)
* Exports results to a CSV (comma seperated) text file saved to User desktop
* CSV file can be opened in Excel or Text Editor for further analysis and review of your data. 

## Data file Location
Please edit Python Script **line 14** to point to the specific Finder path of your Banktivity 6 data file



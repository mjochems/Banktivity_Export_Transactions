# Banktivity Transactions Export

## Background
Banktivity 6 for macOS uses a standard SQLite database saved on your Mac. Python script uses SQL to query this database and return data.

## Python Script
Returns all transaction data (including security trades) and exports results to a CSV (comma seperated) text file saved to User desktop. Script has Read Only access to your database.

## Data file Location
**Please edit Python Script line 14 to point to the specific Finder path of your Banktivity 6 data file**



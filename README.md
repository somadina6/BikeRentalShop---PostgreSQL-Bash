# Bike Rental Shop
## Overview
This project is a simple Bike Rental Shop system developed using PostgreSQL for the database and Bash Scripting for automation. It allows users to rent bikes, return them, and view rental history.

## Requirements
1. _Database Setup:_
- Create a PostgreSQL database for the Bike Rental Shop.
```
createdb -U your_username -e your_database
```
- Load the dump file
```
psql -U your_username -d your_database -a -f path/to/your/dumpfile.sql
```

2. *Bash Scripts*
- Make sure the 'bike-shop.sh'executable.
```
chmod +x bike-shop.sh
```

3. Configuration:
- Update the database connection details in scripts/config.sh with your PostgreSQL credentials.
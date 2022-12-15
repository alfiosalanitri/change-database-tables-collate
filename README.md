# NAME
change-database-tables-collate - Bash script to change charset and collate to database specific tables parsed from txt file

# DESCRIPTION
This script create a backup and convert the collate and charset to all tables parsed from tables.txt file

# INSTALLATION
- `sudo chmod +x /path/to/change-database-tables-collate/change-database-tables-collate`
- `sudo ln -s /path/to/change-database-tables-collate/change-database-tables-collate /usr/local/bin/change-database-tables-collate` (optional)
- `cp tables.txt.example tables.txt`
- set all tables (each for line) into tables.txt

# USAGE
`change-database-tables-collate /path/to/tables.txt database utf8mb4 utf8mb4_unicode_520_ci`
       
# AUTHOR: 
change-database-tables-collate is written by Alfio Salanitri <www.alfiosalanitri.it> and are licensed under the MIT License.

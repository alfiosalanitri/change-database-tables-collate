# NAME
wp-cdtc - Bash script to change charset and collate to database specific tables. Reads the config data from wp-config.php

# DESCRIPTION
This script read wp-config.php file, create a backup and convert the collate and charset to all tables setted into tables.txt file

# INSTALLATION
- `sudo chmod +x /path/to/wordpress-change-database-table-collate/wp-cdtc`
- `ln -s /path/to/wordpress-change-database-table-collate/wp-cdtc /usr/local/bin/wp-cdtc`
- `mv tables.txt.example tables.txt`
- set all tables (each for line) into tables.txt

# USAGE
- `cd /var/www/website`
- `wp-cdtc /path/to/tables.txt utf8mb4 utf8mb4_unicode_520_ci`
       
# AUTHOR: 
wp-cdtc is written by Alfio Salanitri <www.alfiosalanitri.it> and are licensed under the MIT License.

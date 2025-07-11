📦 Database Used:
'art_studio_data – A custom database built containing customer, orders, and art item data.

✅ Backup Process:
- Performed using MySQL Workbench → Server → Data Export
- Export type: Dump Structure and Data
- Output: Dump20250711.sql

The dump file is saved and included in the repository as a BACKUP FILE

✅ Restore Process:
- Performed using MySQL Workbench → Server → Data Import
- Used the Dump20250711.sql file as input
- Restored the file in existing database: "migration_sample"
- Restored all tables and data successfully
- Verified via 'SHOW TABLES;' and 'SELECT * FROM customers;'

The RESTORED database was fully functional and identical to the original.

✅ Outcome:
- Backup and restore process completed without errors
- All data and structure preserved 

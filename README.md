# ETL-Mini-Pipeline-Python-Extract-Transform-Load
This ETL process loads the raw CSV dataset, cleans missing values and duplicates, standardizes column names and types, and creates derived columns such as total_movement and a high_movement flag. The data is then split into suppliers, items, and monthly_movements tables, exported as CSVs, and loaded into a SQLite database. Row counts are validated.

## Folders
- raw/ : Original CSV dataset
- processed/ : Cleaned and transformed CSVs
- output/ : SQLite database
## ETL Steps
1. Load raw CSV dataset.
2. Remove duplicates and fill missing values.
3. Standardize column names and datatypes.
4. Create derived columns: total_movement and high_movement flag.
5. Split into tables: suppliers, items, monthly_movements.
6. Export CSVs and load into SQLite database.
7. Validate row counts before and after transformation.

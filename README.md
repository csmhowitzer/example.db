# A simple portable sqlite testing database

## Prerequisites
- Sqlite3 is installed

1. Clone the repo
2. run `sqlite3 example.db < CreateAllTables.sql`
3. run `sqlite3 example.db < SeedAllTables.sql` 
4. run `sqlite3 example.db < DropAllTables.sql` IFF you have issues, then go back to step #2

## Troubleshooting
---
Ensure that Sqlite version 3 is used. Add the full path and not just the file name when you run the commands. Refer to Sqlite documentation for further issues.

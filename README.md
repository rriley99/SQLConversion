# SQLConversion
The beginning of a project to generally convert MSSQL(T-SQL) queries to PostgreSQL queries

# Top-Level Architecture 
1. Input basic MSSQL query and segment into parts and convert to ANSI-SQL
2. Create mapping for ANSI-SQL to PostgreSQL
3. Validation layer for syntax
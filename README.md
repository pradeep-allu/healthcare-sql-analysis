# Healthcare Data Analysis Using MySQL

A SQL-only project answering 34 business questions on a hospital database.

## Tools
MySQL

## Database
`medical_db` with 4 tables: `patients`, `admissions`, `doctors`, `province_names`

## Files
- `healthcare_queries.sql` - all 34 queries, with the question written above each one

## SQL concepts used
- Filtering: WHERE, LIKE, BETWEEN, IN, IS NULL
- Aggregation: COUNT, SUM, MAX, MIN, GROUP BY, HAVING
- INNER JOINs across patients, admissions and doctors
- UNION ALL, subqueries, CASE statements
- String and date functions: CONCAT, UPPER, LOWER, YEAR, DAY, FLOOR
- UPDATE to replace NULL allergies with 'NKA'

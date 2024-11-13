# Snowflake_Transport

Query a Snowflake database containing data on journeys and transport types in London between 2010 and 2022 to find the most and least popular transport methods. 

The database 'TFL' contains a single table called JOURNEYS, including the following data:

| Column | Definition | Data type |
|--------|------------|-----------|
| `MONTH`| Month in number format | `INTEGER` |
| `YEAR` | Year | `INTEGER` |
| `DAYS` | Number of days in the given month | `INTEGER` |
| `REPORT_DATE` | Date that the data was reported | `DATE` |
| `JOURNEY_TYPE` | Method of transport used | `VARCHAR` |
| `JOURNEYS_MILLIONS` | Millions of journeys, measured in decimals | `FLOAT` |

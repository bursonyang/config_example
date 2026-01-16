# Spark SQL query from Iceberg

To ensure correct time zone conversion when querying TIMESTAMP columns, set spark.sql.session.timeZone before executing the query.

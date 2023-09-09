## Initial Schema

|-- task: string (nullable = true)
 |-- status: string (nullable = true)
 |-- trackID: long (nullable = true)
 |-- server_region: string (nullable = true)
 |-- timestamp: long (nullable = true)
 |-- server: string (nullable = true)

# The following analysis was carried out after cleaning and transforming
- retrieved the number of countries and task carried out
- retrieved the states it was carried out in
- looked at the top ranking task in each country
- performance of each task
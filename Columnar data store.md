> [!quote] from [Wikipedia](https://en.wikipedia.org/wiki/Column-oriented_DBMS)
A **column-oriented DBMS** or **columnar DBMS** is a [database management system](https://en.wikipedia.org/wiki/Database_management_system "Database management system") (DBMS) that stores data tables by [column](https://en.wikipedia.org/wiki/Column_(data_store) "Column (data store)") rather than by row. Benefits include more efficient access to data when only querying a subset of columns (by eliminating the need to read columns that are not relevant), and more options for data compression. However, they are typically less efficient for inserting new data.

While the concept of columnar databases originates from the relational database community, it now covers other systems, including:

- [[Apache Parquet]];
- [Apache Arrow](https://arrow.apache.org/) column-oriented memory format for flat and hierarchical data;
- the [Dremel](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf) paper, describing the underlying principles for a scalable, interactive ad-hoc query system for analysis of read-only nested data, which led to the development of BigQuery.

The [[The Composable Data Management System Manifesto]] uses columnar data stores as one of the key technologies.

#columnar #parquet #arrow


# Database
Database exercises and study material.

A normalized database stores each piece of data only once, usually in specific tables with a relation to one another.
Normalization allows for faster writes, no data redundancy, less database complexity and data consistency (one version of the truth). In other hand, reads may be slower specially when the database is heavyly queried, table joins are required and can become expensive operations due to complex joins. 

Denormalization allows for aster reads, simpler queries and makes data available quickly. In other hand, the writes are slower, the database itself is more complex, there is the risk of data inconsistency and it requires more storage (due to data duplication or agregations stored).
Denormalization is used on previously normalized DBs to increase performace. The starting point of denormalization is a normalized database.

Denormalization techniques:

1. Pre-joining tables
A redundant column(s) will be added to a table in order to avoid a recurrent join with another table.
![](https://github.com/GustyFox/Database/blob/main/PreJoin.jpg)

2. Table splitting
Process of splitting a table, vertically or horizontally, in multiple tables (pre-filtering).
![](https://github.com/GustyFox/Database/blob/main/HorizontalSplit.jpg)
![](https://github.com/GustyFox/Database/blob/main/VerticalSplit.jpg)

3. Calculated Column
![](https://github.com/GustyFox/Database/blob/main/CalculatedColumn.jpg)

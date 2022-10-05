# Communication-Assignment-5

## Overview
This project shows the demo of relational joins. It contains all required queries for the demo.

## Key Topics
Types of relational joins are explained in this project with the code demo.

1. **INNER JOIN:** returns only the rows where matches were found </br>
2. **LEFT JOIN:**	returns matches and all rows from the left listed table </br>
3. **RIGHT JOIN:**	returns matches and all rows from the right listed table </br>
4. **FULL OUTER JOIN:**	returns matches and all rows from both tables </br>

![alt text](https://github.com/vichitrak10/Communication-Assignment-5/blob/main/joins.png)

## DBMS and Table Description:
This queries have been created with the **postgreSQL.**

**storage_sj** : data of storage from the San Jose location </br>
**storage_ok** : data of storage from the Oakland location

```
storage_sj
├── owners            # varchar
├── item_1_sj         # varchar
├── item_2_sj         # varchar
├── item_3_sj         # varchar
```

```
storage_ok
├── owners            # varchar
├── item_1_ok         # varchar
├── item_2_ok         # varchar
├── item_3_ok         # varchar

```

## SQL DDL Description
DDL Used: `drop` and `create`

## How to run:
1. Download the `joins_demo_sql` file.
2. Follow the comments and run queries using any suitable IDE on the postgreSQL.


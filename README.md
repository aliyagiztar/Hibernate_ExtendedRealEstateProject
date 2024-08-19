# REAL ESTATE PROJECT

## VERSION 1.0

### MySQL
```sql
CREATE SCHEMA `real_estate_db` DEFAULT CHARACTER SET utf8 COLLATE utf8_bin;
SCHEMA `real_estate_db` DEFAULT CHARACTER SET utf8 COLLATE utf8_bin ;
```
### PostgreSQL
```postgresql
CREATE SCHEMA real_estate_db AUTHORIZATION postgres;
```

### Oracle
```oracle
CREATE USER real_estate_db IDENTIFIED BY password;
GRANT CONNECT, RESOURCE, DBA TO real_estate_db;
```

### SQL Server
```SQL server
CREATE DATABASE real_estate_db;
GO
ALTER DATABASE real_estate_db COLLATE Latin1_General_BIN;
GO
```


### Property - Varlık (Ev Arsa Dukkan)

- id
- propertyName
- title
- description
- type

### Buyer  - Alıcı

- id
- firstName
- lastName
- email
- phone

###  Seller - Satıcı
- id
- firstName
- lastName
- email
- phone

### Agent - Emlakçı 
- id
- agentName
- email
- phone
- officeAddress


## VERSION 2.0

###  Branch
### Employee
### City
### Address
# Dockerize Hbase
## Installation
1. Clone the repo
2. cd into dir
```
docker-compose exec hbase-master hbase shell
```
## Usage

Creat a table 
```
create 'emp', 'personal data', 'professional data'
```
List tables
```list
```
Insert into table
```put 'emp','1','personal data:name','raju'
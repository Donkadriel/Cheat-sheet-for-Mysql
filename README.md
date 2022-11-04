# Cheat-sheet-for-Mysql

Cheat Sheet for Mysql

## Creating a table

```bash
create table(field_name1, field_name2, etc);
```
##example
```sql
create table table1(id int, reg no. varchar(100), name varchar(200), age varchar(250), sex varchar(100), level varchar(100));
```

## Showing the field names

```sql
describe table1;
```

## Inputing record(row)

```sql
insert into name_of_table(field_name1, field_name2, etc) values ('value1', 'value2', 'value3');
```

##example
```sql
insert into table1(reg no., name, age, sex, level) values ('2022BAG162PLQ', 'dennis', '17', 'M', '100level');
```

## Inputing two or more records(rows)
```sql
insert into name_of_table(field_name1, field_name2, etc) values ('value1', 'value2', 'value3'),('value1', 'value2', 'value3'), ('value1', 'value2', 'value3');
```
##example
```
insert into table1(reg no., name, age, sex, level) values ('2022dtxbHF6567', 'ben', '20', 'M', '300level'), ('2022vjfffKHG64b', 'moses', '21', 'M', '400level'), ('2022RTD67656CVXf8', 'gold', '19', 'F', '200level');
```

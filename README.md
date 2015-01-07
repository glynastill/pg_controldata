pg_controldata
==============

Pl/perlU function to show settings from pg_controldata

Usage
---------

```sql
TEST=# SELECT * FROM public.pg_controldata WHERE setting = 'Database system identifier';
            name            |       setting       
----------------------------+---------------------
 Database system identifier | 5667443312440565226
(1 row)
```


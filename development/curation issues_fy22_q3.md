
This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q3_v1 Fall Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 73280;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 38714;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 38933;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 45224;-
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 73930;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 107689;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 106055;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 138307;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 107625;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 106055;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 13918;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 77619;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 107625;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 123093;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 116371;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 15654;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 45224;
```


![View of SQL Code to Use](/images/2022_Q3_v1_errata_soln_sql.png)

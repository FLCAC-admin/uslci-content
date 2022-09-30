
This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q3_v1 Fall Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 73280;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 73424;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74501;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74470;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74473;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74452;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74547;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74454;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74424;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74375;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74530;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74550;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74442;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74430;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74408;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 74533;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 116595;
```


![View of SQL Code to Use](/images/2022_Q3_v1_errata_soln_sql.png)

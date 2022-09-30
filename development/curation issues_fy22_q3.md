
This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q3_v1 Fall Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 11071;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16288;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16166;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16133;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16308;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16182;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16305;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16212;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16200;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16231;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16188;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16210;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16228;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16291;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 16259;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 140858;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 143657;
```


![View of SQL Code to Use](/images/2022_Q3_v1_errata_soln_sql.png)

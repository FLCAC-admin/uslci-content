
This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q3_v1 Fall Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 197519;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 197663;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198709;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198691;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198712;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198693;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198647;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198614;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198786;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198669;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198663;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198740;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198789;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198769;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198681;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 198772;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 240834;
```


![View of SQL Code to Use](/images/2022_Q3_v1_errata_soln_sql.png)

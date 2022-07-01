This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q2_v1 Summer Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 11412;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 88560;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118803;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118792;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118790;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118767;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118715;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118809;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118816;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118852;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118823;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118827;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118743;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118875;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118777;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 118783;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 128654;
```


![View of SQL Code to Use](/images/2021_Q3_v1_errata_soln_sql.png)

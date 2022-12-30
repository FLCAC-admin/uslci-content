This file folder is used to store files related to the continuing development of USLCI features and curation workflow. 


# 2022_Q4_v1 Winter Release, Erratas Correction Script

A bug has caused some elementary flows to display with 'default providers', that is, processes designated as the provider of the elementary flow input or output. The default providers field is intended for technospheric, i.e., intermediate flows only. To correct this error, you may use the SQL script below in your openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown below.

```sql
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 13201;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14751;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14890;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14785;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14844;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14813;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14773;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14718;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14893;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14795;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14873;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14876;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14797;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14816;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 14767;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 141654;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 143773;
UPDATE tbl_exchanges set F_DEFAULT_PROVIDER = 0 where ID = 148053;
```


![View of SQL Code to Use](/images/2021_Q3_v1_errata_soln_sql.png)

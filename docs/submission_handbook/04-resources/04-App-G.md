# Using the US EPA Data Quality Matrix in openLCA

[**_Return to TOC_**](../00-sub-handbook-landing.md)

## RECOMMENDED: [Use the FLCAC Starter Database](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-H.md)
You may simply use the Federal LCA Commons (FLCAC) Starter Database that already contains the Matrix and updated FLCAC repo data folder structures and move to [STEP 4: Selecting Process Indicators](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-G.md#step-4-select-process-indicators). 

Simply, navigate to the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration). Select the _**Federal_LCA_Commons**_ group and the _**Fed_Commons_Core_Database**_ repo. Download the repository as JSON-LD files and import into an empty database in openLCA. 

See the [USLCI Data Submission Guidelines: Syncing to FLCAC](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-H.md) for complete instructions on how to use the FLCAC Starter Database and sync FLCAC repo data.

## ALTERNATIVELY: [Manual Download & Import](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-G-1.md)

Alternatively, you may download the US EPA Data Quality Matrix directly from the [openLCA Downloads](https://www.openlca.org/download/) page. You may choose this procedure if you are not using the FLCAC Starter Database but you still want to use the EPA Data Quality system in an openLCA database.


<br>
<br>


## DESIGNATING THE MATRIX INSIDE EACH PROCESS

* Next, open your process of interest and on the first **_"General Information"_** tab, you may scroll down to the **_"Data quality"_** section and **_"Process schema"_** field. There is a drop-down menu and the **_"US EPA – Process Pedigree Matrix"_** should now be an option you may select. 
* You will also want to go to the **_"Flow schema"_** field just below and select **_"US EPA – Flow Pedigree Matrix"_** from its drop-down menu such that you can elect data quality indicators at both the process and flow levels.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/3a_Select_Process_Matrix.png)
**_Designating the US EPA Process Pedigree Matrix_**
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/3a_Select_Process_Matrix.png)
**_Designating the US EPA Flow Pedigree Matrix_**
<br>
<br>
<br>


## SELECTING PROCESS INDICATORS

Now, at the **_"Data quality entry"_** field, you may select the **_"not specified"_** hyperlink (still on the first **_"General information"_** tab in the **_"Data quality"_** section). You should now be able click on matrix cells to select entries for **_"Process Review"_** and **_"Process Completeness"_** data quality indicators.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4a_Designate_DQ_Entry.png)
**_Designating the Data Quality Entry at Process Level_**
<br>


![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4b_Select_Process_Indicators.png)

**_Selecting Process Indicator Matrix Cell Entries_**

<br>
<br>
<br>


## SELECTING FLOW INDICATORS

You may now go to the **_"Data quality entry"_** column of any input or output flow on the **_"Inputs/Outputs"_** tab to select entries for the following data quality categories:

- Flow reliability
- Temporal correlation
- Geographical correlation
- Technological correlation
- Data collection methods


![](https://github.com/uslci-admin/uslci-content/blob/dev/images/5_Select_Flow_Indicators.png)

**_Selecting Flow Indicators_**

<br>
<br>

# US EPA Guidance for Selecting Indicators

For guidance on selecting process- and flow-level indicators for your life cycle inventory (LCI) data, please see the [U.S. Environmental Protection Agency (EPA) Guidance on Data Quality Assessment for Life Cycle Inventory Data](https://cfpub.epa.gov/si/si\_public\_record\_report.cfm?Lab=NRMRL&amp;dirEntryId=321834)

---
**If you need to cite the EPA Data Quality Guidance document, use the following citation:**

_Edelen, A. AND W. Ingwersen. Guidance on Data Quality Assessment for Life Cycle Inventory Data. U.S. Environmental Protection Agency, Washington, DC, EPA/600/R-16/096, 2016._

[**_Return to TOC_**](../00-sub-handbook-landing.md)


---

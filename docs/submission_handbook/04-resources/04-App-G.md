# Using the US EPA Data Quality Matrix in openLCA

## Step 1: DOWNLOAD THE MATRIX

You may download the US EPA Data Quality Matrix from the [openLCA Downloads](https://www.openlca.org/download/) page.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/1_openLCA_Downloads_Page_EPA_DQ_Matrix.png)
**_STEP 1: Downloading the US EPA Data Quality Pedigree Matrix Zip File from openLCA Downloads_**
<br>
<br>
<br>

## Step 2: IMPORT THE MATRIX

To add the US EPA Data Quality to your openLCA **_"Indicators & Parameters,"_** you must import it for each database in which you wish to use this pedigree matrix (as the only default matrix available is that from ecoinvent). 
* Thus, you can open the database of interest in openLCA, right-click on the database name, and select **_"Import."_** 
* You may then select **_Linked Data (JSON-LD)_** as the file type and click **_"Next."_** 
* In the **_"Choose Directory,"_** field, designate your **_"Downloads"_** folder and the **_"USEPA\_DataQualitySchemes\_JSON-LDforopenLCA1.6.zip"_** file you just downloaded should appear as an option.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/2_Importing_EPA_DQ_Matrix.png)
**_STEP 2: Importing the US EPA Data Quality Pedigree Matrix Zip File into openLCA_**
<br>
<br>
<br>

## Step 3:DESIGNATE THE MATRIX INSIDE EACH PROCESS

* Select the **_"USEPA\_DataQualitySchemes\_JSON-LDforopenLCA1.6.zip"_** file and click **_"Finish."_** The Pedigree Matrix file is not very large so should import very quickly. 
* Next, open your process of interest and on the first **_"General Information"_** tab, you may scroll down to the **_"Data quality"_** section and **_"Process schema"_** field. There is a drop-down menu and the **_"US EPA – Process Pedigree Matrix"_** should now be an option you may select. 
* You will also want to go to the **_"Flow schema"_** field just below and select **_"US EPA – Flow Pedigree Matrix"_** from its drop-down menu such that you can elect data quality indicators at both the process and flow levels.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/3a_Select_Process_Matrix.png)
**_STEP 3a: Designating the US EPA Process Pedigree Matrix_**
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/3a_Select_Process_Matrix.png)
**_STEP 3b:Designating the US EPA Flow Pedigree Matrix_**
<br>
<br>
<br>

## Step 4: SELECT PROCESS INDICATORS

Now, at the **_"Data quality entry"_** field, you may select the **_"not specified"_** hyperlink (still on the first **_"General information"_** tab in the **_"Data quality"_** section). You should now be able click on matrix cells to select entries for **_"Process Review"_** and **_"Process Completeness"_** data quality indicators.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4a_Designate_DQ_Entry.png)
**_STEP 4a: Designating the Data Quality Entry at Process Level_**
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4b_Select_Process_Indicators.png)
**_STEP 4b: Selecting Process Indicator Matrix Cell Entries_**
<br>
<br>
<br>


## Step 5: SELECT FLOW INDICATORS

You may now go to the **_"Data quality entry"_** column of any input or output flow on the **_"Inputs/Outputs"_** tab to select entries for the following data quality categories:

- Flow reliability
- Temporal correlation
- Geographical correlation
- Technological correlation
- Data collection methods

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/5_Select_Flow_Indicators.png)
**_STEP 5: Selecting Flow Indicators_**
<br>
<br>

# US EPA Guidance for Selecting Indicators

For guidance on selecting process- and flow-level indicators for your life cycle inventory (LCI) data, please see the [U.S. Environmental Protection Agency (EPA) Guidance on Data Quality Assessment for Life Cycle Inventory Data](https://cfpub.epa.gov/si/si\_public\_record\_report.cfm?Lab=NRMRL&amp;dirEntryId=321834)

---
**If you need to cite the EPA Data Quality Guidance document, use the following citation:**

_Edelen, A. AND W. Ingwersen. Guidance on Data Quality Assessment for Life Cycle Inventory Data. U.S. Environmental Protection Agency, Washington, DC, EPA/600/R-16/096, 2016._

---

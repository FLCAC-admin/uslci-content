# Downloading Repositories

[**_Return to TOC_**](../00-sub-handbook-landing.md)

The following procedure demonstrates how to fetch the latest repository-or data in a repository-from the Federal LCA Commons (FLCAC) website, e.g., the USLCI. 
<br>

The USLCI is updated every US Federal fiscal quarter (March 31, June 30, September 30, December 31). You can return to the [FLCAC website](http://www.lcacommons.gov) periodically to obtain the latest version in JSON-LD or ILCD file formats. These and additional file formats (ecospold2 and openLCA .zolca) for the current and past versions of USLCI are available from [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md). The [USLCI Press Release page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/press-release.md) summarizes changes and/or additions made each quarter. In this way, you can always keep a clean, updated copy of the repository for use in your projects (i.e., via import). 
<br>
<br>

**OPTIONAL**: If you want to be notified when there is a newly published version available or errata published on the Press Release page, send an email with _Add me to the stakeholder list_ in the subject line to the [USLCI Data Curator](mailto:rebe.feraldi@lac-group.com?subject=Add%20me%20to%20the%20stakeholder%20list).

## Step 1: CREATE AN EMPTY DATABASE IN DESKTOP OPENLCA APP

First, create an empty database in your openLCA desktop application into which to import the database(s) or desired repository dataset(s) (e.g., USCLI or a select data from USLCI). Right-click in the left panel and select **_New Database_**, name it using no spaces and change the content.  
<br>
**IMPORTANT: CHANGE THE DATABASE CONTENT TO EMPTY!** Do not use **_'Complete reference data'_** or  **_'Unit and flow properties'_** because the FLCAC repos use their own. If you use reference data, you pull in a bunch of elementary flows and category structures not used in the FLCAC. This will render your database bulky and difficult to navigate. 

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Start%20with%20empty%20database%20-%20olca.png)

**_STEP 1: Create an empty database in your openLCA desktop app_**
<br>
<br>
<br>


## Step 2: DOWNLOAD DATASET(S) AND/OR REPO(S)

Navigate to the [FLCAC Website](https://www.lcacommons.gov), at _lcacommons.gov_ and select **_Browse Repositories_**. Once you have entered the Commons, you will see the **_Group/Repository_** list on the right and datasets in the left panel. Select the group and repository from which you wish to download. The USLCI is under the **National_Renewable_Energy_Laboratory** Group and **USLCI** Repository.
<br>
Next, select the green **_Download_** button next to the desired dataset(s) or any dataset if the entire database is desired. Currently, the JSON-LD file format is recommended for openLCA because it is subject to little or no metadata loss when imported into [openLCA].  The ILCD format of the USLCI will result in the loss of comments associated with individual exchanges.
<br>
For an entire database, choose to download the **_"Repository as JSON-LD"_** and save the zipped file somewhere. Leave the files zipped (i.e., do not extract the sub-files). You will import the zipped file in its compressed format from the empty openLCA database you created.
<br>
(br>


![](https://github.com/uslci-admin/uslci-content/blob/dev/images/2.%20Downloading%20from%20FLCAC.png)

<br>
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Download%20Buttons%20-%20Dataset%20OR%20Repository.png)
<br>


**_STEP 2: Downlaoding FLCAC Repo(s)_**

<br>
<br>
<br>


## Step 3: IMPORT THE REPOSITORY

In the openLCA desktop app, select the database you created for this import and right-click to select **_“Import”_** and designate **_“Linked Data (JSON-LD)_**. You may then select the folder to which it was saved.
<br>
NOTE: you will NOT see the actual zipped file; you must first select the folder directory.
<br>
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4.%20Right%20click%20%26%20select%20JSON-LD%20Import.png)

**_STEP 3a: Selecting to Import the zipped JSON-LD Repository File_**
<br>
<br>
<br>
![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Select%20folder%20directory%20for%20import.png)
<br>
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Select%20zipped%20file%20%26%20finish.png)
<br>

**_STEP 3b: Importing the zipped JSON-LD Repository File from the Designated Folder_**
<br>
<br>
<br>



## Step 4: USE THE REPOSITORY IN OPENLCA

Now that you have a clean copy of the desired FLCAC dataset(s) or database(s), repository, ou can use the data in any of your projects. To retain un unmodified copy, it is recommended that you work in a separate openLCA database on your project. You may then import either datasets or an entire database into your project in openLCA. 
<br>
To import an entire FLCAC database into your openLCA project database, right-click on the database name and select **_Import_**, and then, **_“Import entire database”_** of an **_“existing database”_** and select the openLCA FLCAC database into which you imported the FLCAC data. This will import a copy of the FLCAC database into your project leaving the clean copy unmodified.
<br>


![](https://github.com/uslci-admin/uslci-content/blob/dev/images/6.%20Import%20entire%20database.png)
<br>


**_STEP 4a: Right-click on Project Database & Select Import Entire Database_**
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/7.%20Import%20existing%20database.png)

**_STEP 4b: Selecting to Import the Existing Database (Repository) into your Project_**
<br>

<br>
<br>

[**_Return to TOC_**](../00-sub-handbook-landing.md)

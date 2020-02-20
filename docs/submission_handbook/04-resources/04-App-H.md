# Starter Database & Syncing Repo Data to openLCA Desktop

[**_Return to TOC_**](../00-sub-handbook-landing.md)

The following procedure demonstrates how to fetch the latest data from a repository on the Federal LCA Commons Collaboration Server using the NREL USLCI Database as an example.

## Step 1: CREATE AN EMPTY DATABASE IN DESKTOP OPENLCA APP

First, create an empty database in your openLCA desktop application into which you will import the FLCAC Starter Database and desired repository data (e.g., USCLI). In this way, you can always keep a clean, updated copy of the repository for use in other projects (i.e., via import). 

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Create_empty_database.png)

**_STEP 1: Create an empty database in your openLCA desktop app into which you will import the Starter & desired repo datasets_**
<br>
<br>
<br>


## Step 2: DOWNLOAD STARTER and/or DESIRED REPOSITORIES FROM COLLABORATION SERVER

Navigate to the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration). Select the _**Federal_LCA_Commons**_ group and the _**Fed_Commons_Core_Database**_ repo. Download the repository as JSON-LD files. Next, select from which group and which repository you wish to download.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/2.%20Downloading%20from%20FLCAC.png)

**_STEP 2: Federal LCA Commons Collaboration Server Groups & Repositories_**
<br>
<br>
<br>

For both the Starter Database and desired repo datasets, choose to download the **_"Repository as JSON-LD"_** and save the files somewhere. Leave the files compressed. You will import them in their compressed format into the empty database you created in your openLCA desktop app.
<br>
<br>
<br>

## Step 3: IMPORT THE REPOSITORY

In the openLCA desktop app, select the database you created for this import and right-click to select **_“Import”_** and designate **_“Linked Data (JSON-LD)_**. You may then select the zipped file for import from the folder to which it was saved.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/4.%20Right%20click%20%26%20select%20JSON-LD%20Import.png)

**_STEP 3a: Selecting to Import the zipped JSON-LD Repository File_**
<br>
<br>
<br>

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/5.%20Select%20USLCI%20repository%20to%20import.png)
**_STEP 3b: Importing the zipped JSON-LD Repository File from the Designated Folder_**
<br>
<br>
<br>



## Step 4: USE THE REPOSITORY IN OPENLCA

Now you have a clean copy (as a separate database) of the desired Commons repository.  You can use this data in any of your projects by importing an **_“entire database”_** of an **_“existing database”_** and select the clean copy for import into your project database.


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

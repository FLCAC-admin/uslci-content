:arrow_double_down:  USLCI Release Downloads
==================
[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

This page contains dowloads for the [US Life Cycle Inventory Database (USLCI)](https://www.nrel.gov/lci/) release downloads in various data formats. It is intended to support the USLCI data submission process.

The USLCI Database repository and individual datasets are available on the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration) by selecting the **National_Renewable_Energy_Laboratory/USLCI** Group, clicking the **"Download"** button to the right of any element, and selecting the desired format (JSON-LD or ILCD).

**STEP 1:** Navigate to the Federal LCA Commons [Landing Page](https://wwww.lcacommons.gov) and select "Browse Repositories" to enter the Commons.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Browse%20repositories.png)

**_STEP 1: Federal LCA Commons Landing Page_**
<br>
<br>
<br>


**STEP 2:** Once you have entered the Commons, you will see groups on the right and datasets in the left panel. Select from which group and which repository you wish to download. The USLCI is under the **National_Renewable_Energy_Laboratory/USLCI** Group.

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/2.%20Downloading%20from%20FLCAC.png)

**_STEP 2: Federal LCA Commons Collaboration Server -- Groups & Repositories_**
<br>
<br>
<br>

**STEP 3:** Selecting the **"Download"** button to the right of any dataset brings up a pull-down menu allowing you to download either the individual dataset or the entire selected repository in the desired format (JSON-LD or ILCD).

![](https://github.com/uslci-admin/uslci-content/blob/dev/images/Download%20repository.png)

**_STEP 3: Downloading Datasets & Repositories_**
<br>
<br>
<br>





[Table 1](release-downloads.md#table-1-uslci-release-downloads) below also contains download links for current and past USLCI quarter release versions in three data formats: 
* openLCA JSON-LD (.zolca files are discontinued as of 10/2018)
* ecoSpold2
* ILCD

For many users, the JSON-LD (zipped) formats will be the most useful since they are not subject to data/metadata loss when imported into [openLCA].  The other formats are subject to data loss in certain use cases. For example, using ILCD format of the USLCI will result in the loss of comments associated with individual exchanges. EcoSpold file formats only contain processes so flows, indicators, & background data are excluded

Downloads are available starting with USLCI release FY17.Q4.02 and include the current quarter release available on the Federal LCA Commons Collaboration Server. 

Select the desired format type: 
* After 2019.Q3, the JSON-LD and ILCD files are larger in size and you will be re-directed to a dropbox link to download
* For all others, select _"View Raw"_ to download the file on the subsequent GitHubscreen
* For ecoSpold2, only "Processes" export from openLCA so the file size is smaller


<br>

#### Table 1. USLCI release downloads   

| Release | openLCA version | openLCA | JSON-LD | ecoSpold2 | ILCD |   
|:---:|:---:|:---:|:---:|:---:|:--:|     
| FY19.Q4.02 | v1.10.0 | [zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_02_olca1_10_0_zolca.zolca) | [JSON-LD](https://app.box.com/s/ugq6r4lp4votmzdrex6xokgxfdfgdyqf) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_02_olca1_10_0_ecospold2.zip) | [ILCD}(https://app.box.com/s/4f0fcoquczxu9pll2o1gj4brm7377w5z) |
| FY19.Q4.01 | v1.10.0 | no .zolca files this quarter | [JSON-LD](https://app.box.com/s/ljzo0ns7gnowemteroki11ubjaulh5st) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_olca1_10_0_ecospold.zip.zip) |[ILCD](https://app.box.com/s/tlseuabs9130jgjrfoiickp3tu606pzq) |
| FY19.Q3.01 | v1.9.0 | no .zolca files this quarter | [JSON-LD](https://app.box.com/s/lv8mzuyyr33r11cmxfdt9k887w7h0sat) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q3_01_olca1_9_0_ecospold.zip.zip) | [ILCD](https://app.box.com/s/6pc5cha9wv3zb9lye1y6up5sk06ooxmx) |
| FY19.Q2.01 | v1.8.0 |no .zolca files this quarter | [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q2_01_olca1_8_0_json_ld.zip.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q2_01_olca1_8_0_ecospold2.zip.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslcy_fy19_q2_01_olca1_8_0_ilcd.zip.zip) |
| FY18.Q3.01 | v1.7.2 | .zolca files discontinued 10/2018 |  [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy18_q3_01_olca1_7_2_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ilcd.zip) |  
| FY18.Q2.01 | v1.7.2 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0.zolca) |  [JSON-LD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ilcd.zip) |  
| FY18.Q1.01 | v1.5.0 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0.zolca) |  [JSON-LD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0_ilcd.zip) |   
| FY17.Q4.02 | v1.5.0 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0.zolca) | -- | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ilcd.zip) |  

<br>

<br><br><br>



[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)


[openlca]: http://www.openlca.org/download/

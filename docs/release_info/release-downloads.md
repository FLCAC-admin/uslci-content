USLCI Release Downloads
==================
[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

This page contains dowloads for the [US Life Cycle Inventory Database (USLCI)](https://www.nrel.gov/lci/) release downloads in various data formats. It is intended to support the USLCI data submission process.

The USLCI Database repository and individual datasets are also available on the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration) by selecting the **National_Renewable_Energy_Laboratory/USLCI** Group, clicking the **"Download"** button to the right of any element, and selecting the desired format (JSON-LD or ILCD).


[Table 1](release-downloads.md#table-1-uslci-release-downloads) contains download links for each USLCI release in three data formats: 
* openLCA JSON-LD (.zolca files are discontinued as of 10/2018)
* ecoSpold2
* ILCD

For many users, the JSON-LD (zipped) formats will be the most useful since they are not subject to data/metadata loss when imported into [openLCA].  The other formats are subject to data loss in certain use cases. For example, using ILCD format of the USLCI will result in the loss of comments associated with individual exchanges.

Downloads are available starting with USLCI release FY17.Q4.02. 

Select the desired format type: 
* After 2019.Q3, the JSON-LD and ILCD files are larger in size and you will be re-directed to a dropbox link to download
* For all others, select _"View Raw"_ to download the file on the subsequent GitHubscreen
* For ecoSpold2, only "Processes" export from openLCA so the file size is smaller and flows, indicators, & background data are excluded


<br>

#### Table 1. USLCI release downloads   

| Release | openLCA version | openLCA | JSON-LD | ecoSpold2 | ILCD |   
|:---:|:---:|:---:|:---:|:---:|:--:|     
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

# :earth_americas: USLCI Press Releases :newspaper:

[Return to the USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

This page provides quarterly updates and news regarding the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) publishing updates. These updates are compiled by the USLCI Data Curator on the behalf of the [National Renewable Energy Laboratory (NREL)](https://www.nrel.gov/). For more information and publications regarding the creation and evolution of the USLCI, please see NREL's [U.S. Life Cycle Inventory Database](https://www.nrel.gov/lci/2019_Coordination_Report.md) project pages.
<br>

## 2019 Fall Quarter (September 30)
The USLCI quarterly update slated for September 30 ocurred on October 3, 2019. Several improvements and additions were made to the database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) including:

  * Technospheric flows (processes and products) have been re-categorized to be aligned with the NAICS folder structure being adapted by repos of the Federal LCA Commons
  *  The EPA Data Quality System is now integrated into the USLCI to be aligned with the system being adapted by the repos of the Federal LCA Commons (see the [relevant section in the USLCI Data Submission Guidelines](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-G.md#using-the-us-epa-data-quality-matrix-in-openlca) for details on how to use this system in openLCA)
  *  Updated PET data (and supply chain links) from NAPCOR/ACC are now available
  *  New electronic scanner data are available from Kodak-Alaris
  *  Agricultural, utility, and transport products have been decoupled from the geographic and temporal scope of their parent processes to eliminate duplicate flows and allow end-users to designate a default provider for products having more than one parent process in openLCA
  *  Several conversion factors have been inserted for natural gas and CO2 emissions corrected for diesel combustion
  *  Coal extraction data have been phased out as they are now superceded by those available in the [NETL Coal Repository](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Energy_Technology_Lab) on the Federal LCA Commons.
  *  Several outdated and duplicate flows have been eliminated and flow nomenclature improved
  
Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

The Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may "Browse Repositories" if you want to explore other data becoming available from Federal LCA Commons member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the December 31, 2019 Winter release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md)](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md).

## 2019 Summer Quarter (June 30)
The USLCI quarterly update occurred on June 30, 2019. The most recent udate of the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) is now available on the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), which contains multiple group repositories. For this update, there was a display correction for the hydrogen synthesis dataset, some corrections to the allocation settings for some wood manufacturing processes, and several deletions of old providers. Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the September 30, Fall 2019 release date. We look forward to hearing from you soon.

NREL is publishing a coordination report to provide information about the US Federal Life Cycle Assessment Commons (FLCAC). The FLCAC is not only a public data source but also a repository for data developed under Energy Efficiency & Renewable Energy (EERE) programs. The FLCAC Commons Working Group is coordinating and focusing efforts to improve the standardization of data documentation, formatting, and nomenclature to ensure lossless data loading and accurate data representation in the repository server. The report introduces LCA within EERE programs, describes the current status of the FLCAC, and iterates opportunities for the FLCAC to support EERE goals and objectives. See the [full Coordination Report here](https://github.com/uslci-admin/uslci-content/blob/dev/docs/coordination_report/toc.md).

Finally a note of explanation on database deletions in updates on which we have received inquiries: Datasets deleted are always still available in an archive managed by NREL (previous USLCI database versions are available at:[https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md)](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md). However, when the change logs indicate the dataset was an outdated provider, it means that there is a newer (i.e., more updated) equivalent available in the database from the same data compiler. An example for the last dataset was petroleum refining compiled by ERG--there were 2 petroleum refining datasets from the ERG but one was outdated and many users were unsure as to which one to select for linking in upstream processes. One of the main issues with this instance is that one was referred to as "crude oil refining" and the other as "petroleum refining"--however, they referred to the same process. This occurred because nomenclature standards continue to be improved as the USLCI strives to coordinate with other agencies in the multi-agency collaboration that is the Federal LCA Commons. NREL will continue to resolve these types of issues in the USLCI by including only the latest (i.e., most appropriate) datasets for performing LCAs. An exception is if you were performing a retrospective study and even then, some of the methodologies are updated from one provider to another. Please let me know if you have further questions regarding this issue or archived datasets. The same explanation applies to corrugated products--these datasets have been updated so the older ones are no longer intended for use but are still available in archived versions of the USLCI database.

## 2019 - Spring Quarter (March 31)
The USLCI quarterly update occurred on March 31, 2019. There were no new data or data updates so there is no change log. Please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the June 30, Summer 2019 release date. We look forward to hearing from you soon.

<br>

## 2018 - Winter Quarter (December 21)
The USLCI quarterly update occurred on December 21, 2018 and contained no new data. The next update will occur March 31, 2019. Please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the Spring 2019 release date. We look forward to hearing from you soon.

<br>


## [2018 - Fall Quarter (September 30)](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/press-release/2018_q3.md)
The most recent udate of the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) is now available on the newly created [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) (_beta version_), which contains multiple group repositories.

<br>
<br>

---
**NOTE: If you need to cite the USLCI Database, use the following format:**

_"U.S. Life Cycle Inventory Database." (2012). National Renewable Energy Laboratory, 2012. Accessed November 19, 2012: [https://www.lcacommons.gov/nrel/search](https://www.lcacommons.gov/nrel/search)_

---

[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

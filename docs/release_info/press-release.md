# :earth_americas: USLCI Press Releases :newspaper:

[Return to the USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

This page provides quarterly updates and news regarding the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) publishing updates. The USLCI is updated quarterly based on the [U.S. Federal Government Fiscal Calendar](https://www.senate.gov/reference/glossary_term/fiscal_year.htm). These updates are compiled by the USLCI Data Curator on the behalf of the [National Renewable Energy Laboratory (NREL)](https://www.nrel.gov/). For more information and publications regarding the creation and evolution of the USLCI, please see NREL's [U.S. Life Cycle Inventory Database](https://www.nrel.gov/lci/2019_Coordination_Report.md) project pages.
<br>

## 2020 Winter Mid-Quarter (Scheduled March 31, Occurred April 24)

This USLCI Database release occurred on April 22, 2020 to the USLCI database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), intended as the normal fiscal quarter release scheduled for March 31, 2020 to align with several improvements going forward:

- Addition of 4 processes for asphalt binder from the Asphalt Institute
- Corrections to units for volume and energy units for liquid fuels and electricity exchanges, respectively
- Improvements to the USLCI adaptation of the Federal Elementary Flow List (FEDEFL)

Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details.

Please note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may _"Browse Repositories"_ if you want to explore other data becoming available from Federal LCA Commons (FLCAC) member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the next June 30, 2020 Summer release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).

<br>

**Asphalt Binder Datasets**

Life cycle inventory (LCI) data for four (4) new processes were added to the USLCI:

  1) Asphalt binder, 0.5% polyphosphoric acid (PPA), consumption mix, at terminal, from crude oil, 0.5% polyphosphoric acid
  2) Asphalt binder, 3.5% styrene-butadiene-styrene (SBS), consumption mix, at terminal, from crude oil, 3.5% styrene-butadiene-styrene
  3) Asphalt binder, 8% ground rubber tire (GRT), consumption mix, at terminal, from crude oil, 8% ground rubber tire
  4) Asphalt binder, no additives, consumption mix, at terminal, from crude oil

These data were compiled by [Sphera](https://sphera.com/) LCA consultants (who [recently acquired ThinkStep](https://sphera.com/news/sphera-signs-agreement-to-acquire-thinkstep/)) for the [Asphalt Institute](http://asphaltinstitute.org/). The LCA Report is available [here](http://www.asphaltinstitute.org/engineering/lca-study-on-asphalt-binders/). 

The product boundary begins with crude oil input to the refinery and ends at the asphalt terminal. Refining steps relevant to the production of asphalt binder include atmospheric distillation and vacuum distillation. The LCI data are system-level and represent the annual industry average for the US and Canada for 12 consecutive months during the 2015 and 2016 calendar years.

Please see the process metadata and/or the report for more information.

**Transport &amp; Resin Corrections:**

Over 1800 exchanges in the USLCI were corrected to reflect the correct units for 22 liquid fuels and chemicals and 54 electricity products due to a non-universal database units error at flow exchanges (i.e., many volume units were in cubic meters needing adjustment to liters and many electricity exchanges were in MJ units needing adjustment to kWh). This database error occurred in Spring quarter 2019 and was detected Winter 2019. Partial corrections were made (to transport modules) for the last Mid-Quarter update and the rest corrected this Spring 2020 quarter. USLCI end-users should use the 2020 USLCI database version to adjust models accordingly.

The volume units error was causing artificial over-estimation of fuel requirements (by factor of 1000 L-to-m3 conversion) for some but not all of the exchanges for the following liquid chemicals and fuels:

-  Acetone, liquid
-  Butyl acetate, liquid
-  Disposal, liquid waste, unspecified to waste water treatment
-  Ethanol, denatured, corn stover, biochemical
-  Gasoline, used in personal vehicle
-  Isobutyl acetate, liquid
-  Naphtha, at regional storage
-  Treatment, electrocoating wastewater, unspecified treatment
-  Diesel, at refinery
-  Diesel, combusted in industrial boiler
-  Diesel, combusted in industrial equipment
-  Gasoline, at refinery
-  Gasoline, combusted in equipment
-  Gasoline, combusted in equipment, at pulp and paper mill (EXCL.)
-  Kerosene, at refinery
-  Liquefied petroleum gas, at refinery
-  Liquefied petroleum gas, combusted in industrial boiler
-  LPG, combusted in industrial boiler, at pulp and paper mill (EXCL.)
-  Natural gas, combusted in industrial equipment
-  Residual fuel oil, at refinery
-  Residual fuel oil, combusted in industrial boiler
-  RFO, combusted in industrial boiler, at pulp and paper mill (EXCL.)


The energy units error was causing under-estimation of energy requirements (by a factor of 3.6 MJ-to-kWh conversion) for electricity at many processes:

- Electricity from hydro
- Electricity, alumina refining regions
- Electricity, aluminum smelting and ingot casting regions
- Electricity, anthracite coal, at power plant
- Electricity, at bauxite mining regions
- Electricity, at bleached kraft market pulp mill
- Electricity, at coated freesheet mill
- Electricity, at coated mechanical paper mill
- Electricity, at cogen
- Electricity, at cogen, for natural gas turbine
- Electricity, at grid
- Electricity, at grid, BC
- Electricity, at grid, MB
- Electricity, at grid, NB
- Electricity, at grid, ON
- Electricity, at grid, QC
- Electricity, at unbleached kraft bag and sack paper mill
- Electricity, at uncoated freesheet mill
- Electricity, at uncoated mechanical paper mill
- Electricity, at wind power plant, unspecified
- Electricity, biomass, at power plant
- Electricity, biomass, gas, landfill, at power plant
- Electricity, biomass, gas, unspecified, at power plant
- Electricity, biomass, liquid, sludge, at power plant
- Electricity, biomass, solid, agriculture by-products, at power plant
- Electricity, biomass, solid, biogenic MSW, at power plant
- Electricity, biomass,liquid, unspecified, at power plant
- Electricity, biomass,solid, unspecified, at power plant
- Electricity, bituminous coal, at power plant
- Electricity, cogenerated, at plant
- Electricity, diesel, at power plant
- Electricity, fossil, unspecified, at power plant
- Electricity, from renewable source, unspecified
- Electricity, geothermal, unspecified
- Electricity, hydropower, at power plant, unspecified
- Electricity, hydropower, at run-of-river power plant
- Electricity, lignite coal, at power plant
- Electricity, low voltage, at grid
- Electricity, low voltage, at grid/CN U
- Electricity, MSW, non-biogenic, at power plant
- Electricity, natural gas, at power plant
- Electricity, nuclear, at power plant
- Electricity, other fuels, at power plant, unspecified
- Electricity, other fuels, unspecified, at power plant
- Electricity, other gases, unspecified, at power plant
- Electricity, petroleum coke, at power plant
- Electricity, petroleum, waste oil, at power plant
- Electricity, photovoltaic, unspecified
- Electricity, residual fuel oil, at power plant
- Electricity, solar, unspecified, at power plant
- Electricity, tire derived fuel, at power plant
- Electricity, waste oil, at power plant
- Electricity; onsite boiler; hardwood mill; average
- Electricity; onsite boiler; softwood mill; average

**Federal Elementary Flow List (FEDEFL)**

This release corrected some elementary flows according to the Federal Elementary Flow List (FEDEFL). Some water emissions to water flows were being erroneously used as input exchanges so these flows were converted to be 'resource' flows as intended.

Please note that there has been a release of [TRACI 2.1 LCIA Method](https://www.lcacommons.gov/lca-collaboration/US\_Environmental\_Protection\_Agency/TRACI) repo on the FLCAC server using the FEDEFL, enabling the use of the TRACI 2.1 method on USLCI compatible with the implementation of the FEDEFL.

The US EPA, the lead agency on the FEDEFL, worked with NREL to help map and convert the USLCI data to the FEDEFL. The USLCI is the first large Federal LCA Commons (FLCAC) dataset to use the FEDEFL. The FEDEFL will become a part of the core database structure across FLCAC repositories. The FEDEFL will provide greater standardization and interoperability for Federal LCA data and can also serve as a standard for elementary flows for a broader community.




For more information regarding any of these changes, contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) or the [USLCI Administrator](mailto:lci@nrel.gov).

<br>
<br>
<br>


## 2019 Winter Quarter (December 31)


The USLCI quarterly update slated for December 31 occurred on January 1, 2020. Several improvements, reviesions, and deltions were implemented to the database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) including:

  * The word "CUTOFF" has been removed from technospheric flows not having a producing process in the USLCI; however, all cutoff flows are categorized in the same Flows\Technosphere Flows\CUTOFF Flows folder and display within processes with this categorization, which helps identify provenance.
  *  Over 19,000 orphan flows have been identified and eliminated from the USLCI (i.e., those not linked to any exchanges)
  *  Updated PET data (and supply chain links) from NAPCOR/ACC are now available
  *  Several flows erroneously categorized as an 'elementary-type' flow have been corrected to display as technosphere-type' or 'waste-type' flows and categorized in the Flows\Technosphere Flows folder accordingly.
  *  A new folder with 'technosphere-type' flows only has been established for Ecosystem Services (e.g., land transformation flows)
  *  Several display errors from the PET resin supply chain have been corrected 
  *  Several outdated and duplicate flows have been eliminated and flow nomenclature improved
  
Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

Note, shortly there will be a version 2 of this 2019 Winter (Q4) release that will eliminate CORRIM data duplicates that now have updated versions available in the [USFS CORRIM Repository](https://www.lcacommons.gov/lca-collaboration/US_Forest_Service_Forest_Products_Lab/CORRIM) on the Federal LCA Commons. This mid-quarter version will also have a complete mapping of elementary flows to the newly developed [Federal Elementary Flow List](https://cfpub.epa.gov/si/si_public_record_Report.cfm?dirEntryId=347251&Lab=NRMRL), developed by the EPA.

Also, note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may "Browse Repositories" if you want to explore other data becoming available from Federal LCA Commons member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the March 31, 2020 Spring release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md).

## 2019 Fall Quarter (October 23)

Currently, the Federal LCA Commons Collaboration Server is experiencing a bug so downloading repositories from the server is on hold until the issue is addressed. In the meantime, NREL has updated the [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page to include the current USLCI release version. The JSON-LD and ILCD file sizes are larger than ecoSpold2 so these links will re-direct you to a Dropbox page to download the zip files. If importing the files into openLCA, leave the files zipped and select from the openLCA importer tool.

For many users, the JSON-LD (zipped) formats will be the most useful since they are not subject to data/metadata loss when imported into [openLCA].  The other formats are subject to data loss in certain use cases. For example, using ILCD format of the USLCI will result in the loss of comments associated with individual exchanges. EcoSpold file formats only contain processes so flows, indicators, & background data are excluded.




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

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md).

## 2019 Summer Quarter (June 30)
The USLCI quarterly update occurred on June 30, 2019. The most recent udate of the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) is now available on the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), which contains multiple group repositories. For this update, there was a display correction for the hydrogen synthesis dataset, some corrections to the allocation settings for some wood manufacturing processes, and several deletions of old providers. Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the USLCI Data Curator (rebe.feraldi@lac-group.com) if you have any data/metadata publishing goals for the September 30, Fall 2019 release date. We look forward to hearing from you soon.

NREL is publishing a coordination report to provide information about the US Federal Life Cycle Assessment Commons (FLCAC). The FLCAC is not only a public data source but also a repository for data developed under Energy Efficiency & Renewable Energy (EERE) programs. The FLCAC Commons Working Group is coordinating and focusing efforts to improve the standardization of data documentation, formatting, and nomenclature to ensure lossless data loading and accurate data representation in the repository server. The report introduces LCA within EERE programs, describes the current status of the FLCAC, and iterates opportunities for the FLCAC to support EERE goals and objectives. See the [full Coordination Report here](https://github.com/uslci-admin/uslci-content/blob/dev/docs/coordination_report/toc.md).

Finally a note of explanation on database deletions in updates on which we have received inquiries: Datasets deleted are always still available in an archive managed by NREL (previous USLCI database versions are available on the main Wiki's [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page. However, when the [Change Logs](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) indicate the dataset was an "outdated provider," this means that there is a newer (i.e., more updated) equivalent dataset available in the database from the same data compiler. An example for the last dataset was petroleum refining compiled by ERG--there were 2 petroleum refining datasets from the ERG but one was outdated and many users were unsure as to which one to select for linking in upstream processes. One of the main issues with this instance is that one was referred to as "crude oil refining" and the other as "petroleum refining"--however, they referred to the same process. This occurred because nomenclature standards continue to be improved as the USLCI strives to coordinate with other agencies in the multi-agency collaboration that is the Federal LCA Commons. NREL will continue to resolve these types of issues in the USLCI by including only the latest (i.e., most appropriate) datasets for performing LCAs. An exception is if you were performing a retrospective study and even then, some of the methodologies are updated from one provider to another. Please let me know if you have further questions regarding this issue or archived datasets. The same explanation applies to corrugated products--these datasets have been updated so the older ones are no longer intended for use but are still available in archived versions of the USLCI database.

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

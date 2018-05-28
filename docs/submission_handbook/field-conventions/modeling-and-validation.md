# Modeling and Validation Field Conventions

[**_Return to TOC_**](../00-sub-handbook-landing.md)

[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)

This set of tables includes the following conventions for this tab in openLCA:
- [Modeling and Validation](#modeling-and-validation)
- [Data Source Information](#data-source-information)
- [Process Evaluation and Validation](#process-evaluation-and-validation)
- [Sources](#sources)<br>


<a id="modeling-and-validation"></a> 
## Modeling and Validation

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Process type|Indication of whether the data represent a unit or system process, where a system process is an LCI result.|_Unit process_|
|(M) LCI method|Indicate whether the LCI method was attributional, consequential, input/output, hybrid, etc.|_Attributional_|
|(M) Modeling constants|State the primary assumptions used to create this process; for multi-functional processes, describe how emissions were allocated among the co-products; provide allocation factors and supporting calculations as necessary|_This process was adapted from an ecoinvent process for wood pellet manufacturing for pellets of a specific energy value. The process weight factors were adapted for the energy density of a typical US biomass fuel._|
|(M) Data completeness|A qualitative and quantitative description of missing and excluded data. This field is comprised of three elements:<br><br>**1. TREATMENT OF MISSING ENVIRONMENTAL DATA**<br>List and describe accounting methods for missing environmental data (e.g., cut-off rules) and/or intentional environmental data omissions. As applicable, discuss missing data related to the following: air used in combustion; nutrients to/from air and soil; occupied area; particulate matter; transformed area; water withdrawal; and other directly extracted resources.<br><br>**2. TREATMENT OF MISSING TECHNOSPHERE DATA**<br>List and describe accounting methods for missing technosphere data and/or intentional technosphere data omissions. As applicable, discuss missing data related to the following: co-production; consumption of ancillary materials such as energy, fuel, and product materials; transport; and water production or use.<br><br>**3. MASS BALANCE**<br>Either quantify and describe the mass imbalance ((mass of material outputs - mass of material inputs)/mass of material outputs) or state, "The mass balance for this process was not calculated."|_TREATMENT OF MISSING ENVIRONMENTAL DATA_<br>_Elementary flows are cut-off at less than 1% based on environmental relevance._<br>_TREATMENT OF MISSING TECHNOSPHERE DATA_<br>_Intermediate flows are cut-off at less than 1% based on environmental relevance. Capital equipment is not included in this unit process._<br>_MASS BALANCE_<br>_The mass imbalance for this unit process is -17.87 kg (-0.72%)._|
|(O) Data selection|The principle that have been used when selecting which data to include in the process; e.g., the principle applied for choosing data sources to use for different parts of the process.|_Source 1 disaggregated waste inputs and listed heating values and emission factors for the incineration; whereas, Source 2 had only heating values for waste flow inputs. Therefore, Source 2 waste heating values were excluded from the averages._|
|(M) Data treatment|Detailed description of the methods and assumptions used to transform primary and secondary data into flow quantities through recalculating, reformatting, aggregation, or proxy data. Also includes a description of the data quality according to LCAC convention|_Primary data were taken from precise engineering specifications specific to this unit process. These data were then transformed into material and energy flows using the methodology described in Wood (2016) which is due to be released in April 2017. The Wood (2016) methodology is almost identical to the methodology described in Wood (2012) which is an ISO 14044 compliant, peer-reviewed LCA report of three Kodak scanners (Kodak i2800; i2600; and i2400). Secondary data were taken from the ecoinvent 3.2 database (Wernet et al. 2016) and the US Life Cycle Inventory Database (National Renewable Energy Laboratory 2016). The data were global except where otherwise specified._|

<br>

  <a id="data-source-information"></a> 
  ## Data Source Information
  
| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Sampling procedure|Detailed description of how boundary conditions were defined, how data were collected, and how uncertainty is estimated. This field is comprised of three elements:<br><br>BOUNDARY CONDITIONS<br>A description of what is included and excluded from the system boundaries.<br><br>DATA COLLECTION<br>A description of how data were collected for this unit process.<br><br>UNCERTAINTY ESTIMATION<br>A description of if and how uncertainty was calculated for this process. If uncertainty was not calculated, this should be explicitly stated.|_BOUNDARY CONDITIONS_<br>_The system boundary includes: 1) the transport of raw materials to multiple manufacturing facilities where various subcomponents are produced; 2) the manufacture of subcomponents; 3) the transport of subcomponents to a different manufacturing plant for final assembly; 4) the assembly of subcomponents into a complete scanner; and 5) the transport of generated waste from the manufacturing facilities to a municipal solid waste landfill. The following processes and life cycle phases fall outside the system boundary: 1) packaging of the completed scanner; 2) all transport downstream of the assembly plant gate; 3) sale of product; 4) product use phase; and 5) end-of-life phase (including recycling)._<br><br>_DATA COLLECTION_<br>_For material inputs, data collection was based on scanner specifications provided by the manufacturer. Other inputs (e.g. energy; waste transport and disposal) were calculated on the basis of quantity of input per kg of scanner produced._<br><br>_UNCERTAINTY ESTIMATION_<br>_Uncertainty was estimated based on engineering judgment. Material inputs had less uncertainty because they were based off of precise engineering specifications. Other inputs (e.g. energy; waste transport and disposal) had more uncertainty._|
|(M) Data collection period|Time period in which the data were collected.|_All primary data were collected from 2015 to 2016. Secondary data were collected from 2005-2016 (NREL 2016; Wernet et al. 2016)._|

<a id="process-evaluation-and-validation"></a> 
## Process Evaluation and Validation

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Reviewer|Reference to the openLCA Actor who reviewed the dataset.|_Jay Mathewson_|
|(O) Data set other evaluation|End date for the time period that the process represents. The date format is MM/DD/YYYY|_12/31/2017_|
|M Description|Additional review information pertaining to the dataset (e.g., single or panel review, internal or third party, data entry proofreading, mass balance verification, data documentation review, etc.).|_The LCA study that produced this unit process was critically reviewed per ISO 14040 and 14044 standards by Dr. Thomas Gloria of Industrial Ecology Consultants._|

<a id="sources"></a> 
## Sources

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Sources|Reference to the openLCA Source(s) used to compile the data.|_Wernet et al. (2016) The ecoinvent database version 3 (part I): overview and methodology._<br>_Institute for Environment and Sustainablility. (2010). General guide for Life Cycle Assessment - Detailed guidance._<br>_National Renewable Energy Laboratory (2016). US Life Cycle Inventory Database. Sustainable Solutions Corporation. (2016). IMA-NA Calcium Carbonate Life Cycle Assessment_|

<br><br><br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)
<br><br>
[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)
<br><br><br>



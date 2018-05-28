# General Information Field Conventions

[**_Return to TOC_**](../00-sub-handbook-landing.md)

[**Return to Metadata Guidance Tables List**](./05-field-conventions.md)

## General Information

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Name|Process name based on the [USLCI naming convention]((../04-resources/04-App-E.md); the name should reflect the product or service it represents; the product reference output is given the same name as the process name; the naming conventions are as follows:<br><br>**Base name; treatment, routes, standards; production type, location type; quantitative flow properties**<br><br>The base name is a general descriptive name of the process using technical language. The technical name should be given as it is used in the respective industry or toward their customers. The standards include qualitative information about the process in technical terms (see Rules 12-17 [Appendix D: ILCD Nomenclature Rules](../04-resources/04-App-D.md) or the full [ILCD Handbook](http://eplca.jrc.ec.europa.eu/uploads/MANPROJ-PR-ILCD-Handbook-Nomenclature-and-other-conventions-first-edition-ISBN-fin-v1.0-E.pdf) for a list of potential descriptive terms). The quantitative process properties further specify information on process in technical quantitative term(s).<br><br>Base name and treatment/routes/standards are mandatory; production/location type is mandatory if relevant to the process (if not, it can be ignored); the location type of availability (LCAC) is designated only if the process is not a mix; if the process is a production or consumption mix, the mix type is indicated; finally, any essential quantitative properties of the product or process should be included.<br><br>For consistent nomenclature, use the following guidelines:<br><ul><li>separate components with a semi-colon</li><li>separate elements within a component with a comma</li><li>abbreviations should be avoided</li><li>limit names to 220 characters</li><ul>|**Example with 3 components**<br>_Clinker; average mineral mix, at kiln, 1415 kg/m3_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><br>**Example with 3 components**<br>_Transport; long-haul truck, diesel powered; trip length > 200 mi_<br><br>**Example with 2 components**<br>_Scanner manufacture; Kodak Alaris i940 desktop manufacturing process_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|(M) Category|The category/subcategories schema follows North American Industry Classification System (NAICS). Categorize process by placing it in the proper folder in the process tree (using the USLCI categorization convention as a guide); Once the JSON-LD USLCI Database zip file has been uploaded, the categories display and can guide the placement of your datasets in the USLCI categorization scheme; use the format main category (4-digit NAICS)/subcategory (3-digit NAICS) shema (see [Appendix E: 2017 NAICS United States Structure](../04-resources/04-App-E.md)).|_Chemical Manufacturing/All Other Basic Inorganic Chemical Manufacturing_<br><br>_Paper Manufacturing/Pulp, Paper, & Paperboard Mills/Paper_|
|(A) Version|Per the ILCD, the data set version; the first two digits indicate major updates, while the second two digits refer to minor revisions and error corrections; the final three digits are used for automatic and internal version counting during dataset development; Unless discussed in advance with the Data Curator, the value will be generated automatically by openLCA|_01.00.000_|
  |(A) UUID|32-digit Universally Unique Identifier (UUID) for the data set|_961fad56-bde2-4fbe-8895-5be03461729b_|
  |(A) Last change|The date and time when the dataset was last saved|_2018-04-01T17:38:55-0600_|
  |(M) Infrastructure process|Checking this box indicates that the process includes infrastructure requirements in its inventory. Leave this box unchecked if infrastructure requirements are not included in the process|_False_|
  
  ## Quantitative Reference
  
  | Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Quantitative reference|When you create a new process, this is the basis by which all the process flows are scaled; often the functional unit; the quantitative reference must be one of the process output flows; the output flows appear in a pull-down menu by default (See Rule 16: “Quantitative flow properties” name field, in [Appendix D: ILCD Nomenclature Rules](../04-resources/04-App-D.md).|_Scanner; Kodak Alaris i940 desktop scanner; Global supply chain; 1 unit, 1.55 kg_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

## Time

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Start date|Start date for the time period that the process represents. The date format is MM/DD/YYYY|_01/01/2017_|
|(M) End date|End date for the time period that the process represents. The date format is MM/DD/YYYY|_12/31/2017_|
|M Description|Additional information regarding the temporal characteristics and period that the process represents. Examples can include the period for which the process is valid, any temporal aggregation, data collection period, seasonal/annual variations, and carbon provenance|_This unit process is representative of operations from 2014-2015. Water consumption varied seasonally but was averaged over an annual period._|

## Geography

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Location|The geographic area to which the unit process data were collected or refer. NREL recommends that the geography reference the highest geographic resolution possible. Indicate ‘US’ unless higher geographic resolution is available. Use ISO 3166-2 code indicating the process’ geographic location if it is a US state. If the data are not a US state, also describe the locations in the geography ‘Description’ field|_US-CO_|
|(O) KML|Keyhole Markup Language (KML) file which allows users to create a coordinate point, bounding box or polygon indicating the geographic area the process represents; external KML files cannot be submitted|_Polygon [-77.92, 39.55… -77.92, 39.55]_|
|(M) Description|Description of the process' geographic representativeness and any geographic aggregation methods|_This process is representative of production in the state of Colorado. Production data were aggregated across five sites ranging from eastern to western Colorado._&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

## Technology
| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Description|A short (i.e., 1-3 paragraphs), general description of the process intended technical scope, representativeness, and relevance. Include the following information (if applicable):&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><ul><li>Process design including sub-processes, unit operations, and/or other activities (anthropogenic or natural) included in the process.</li><li>Material selection and quality.</li><li>Operational conditions.</li><li>A description of any fate and transport modeling.</li><ul>|_This process represents the production of "Calcium carbonate, ground, 20 microns, at plant" using average technologies for the United States from 2015-2016.<br><br>The process includes three sub-processes: Quarry Operations; Transport and Plant Processing. Quarry Operations includes the following unit operations: mechanical extraction; primary crushing; screening; and intermediate storage of calcium carbonate rock (marble, limestone, or chalk). Transport includes the transport of materials from Quarry Operations to Plant Processing via barge, train, or truck. Plant processing which includes jaw crushing, washing, impact crushing, ball milling to particle size, and then classifying. Material selection and quality represent industry averages from the contiguous United States. Operational conditions represent industry averages from the contiguous United States.Fate and transport modeling was not considered for this process._|
  
  ## Data Quality
  
  | Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Process schema|Currently, the only default process schema for data quality available in openLCA is adapted from ecoinvent; other data quality schemes may be downloaded from openLCA and imported. It is preferred that you use the US EPA data quality system for the process schema|_US EPA data quality system_|
|(M) Data quality entry|Selecting the “not specified” link opens the Pedigree matrix, in which you can select the cardinal indicators for flow reliability, temporal correlation, geographical correlation, further technological correlation, and data collection methods (i.e., completeness). For details on the data quality scheme, see the pull-down menu descriptors in openLCA or the [EPA 2016 Guidance Document on Data Quality Assessment for LCI Data](https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=528687).|_(1;2;1;1;1)_|
|(O) Flow schema|Currently, the only default flow schema for data quality available in openLCA is adapted from ecoinvent; it is preferred that you use the US EPA data quality system for the flow schema.|_US EPA data quality system_|
|(O) Social schema|Currently, the only default social schema for data quality available in openLCA is adapted from ecoinvent|_ecoinvent data quality system_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

<br><br><br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)
<br><br>
[**Return to Metadata Guidance Tables List**](./05-field-conventions.md)
<br><br><br>





  
  
  
  



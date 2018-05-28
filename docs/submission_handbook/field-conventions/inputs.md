# Inputs Field Conventions

[**_Return to TOC_**](../00-sub-handbook-landing.md)

[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)

This table includes conventions for the following set of fields in this tab of openLCA:

- [Inputs](#inputs)


<br>


<a id="inputs"></a> 
## Inputs

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(A) Flow|Flow name based on the USLCI Naming Convention (see [General Information, Name Field Conventions](./general-info.md#general-information). For general elementary flow conventions, see Rules 2-9/18 and for general product/process flow names, see Rules 12-17 of [Appendix D: ILCD Nomenclature Rules](../04-resources/04-App-D.md). See the full [ILCD Handbook](http://eplca.jrc.ec.europa.eu/uploads/MANPROJ-PR-ILCD-Handbook-Nomenclature-and-other-conventions-first-edition-ISBN-fin-v1.0-E.pdf) for detailed conventions|_EPS virgin resin manufacture; batch suspension polymerization; industry average, at plant_|
|(A) Category|Flow category based on the USLCI Categorization Convention (see [General Information, Name Field Conventions](../field-conventions/general-info.md#general-information))|_Chemical Manufacturing/Resin, Synthetic Rubber, and Artificial Synthetic Fibers and Filaments Manufacturing_|
|(M) Amount|Flow quantity|_0.484_|
|(M) Unit|Flow unit; the openLCA software includes a set of unit groups and units; these units must be used to ensure proper data importation. If these units are not appropriate for one or more of your dataset flows, let your Data Curator know and NREL will assist in adding a unit to the list|_kg_|
|(O) Costs/Revenues|This field is provided for documenting life cycle costing (LCC) data; the currency and costs may be provided for each flow; the costs per unit are automatically generated based on this information and flow amount|_1.45 USD/kg_|
|(O) Uncertainty|Describe flow's data uncertainty. This information is not required, but if provided it increases the process' usefulness. The distribution type, mean, and standard deviation may be provided|_Normal distribution_<br>_Mean = 0.484_<br>_Standard deviation = 0.15_|
|(O) Avoided waste|If there is a scrap or waste flow that is utilized in your process, the flow may be listed as an input to your dataset and marked as an avoided waste|_Bottle waste_|
|(O) Provider|If the flow is produced by more than one process, you may use the drop-down menu to select a default provider|_Aluminum production; hot rolling; production mix, at plant_|
|(O) Data quality entry|Describe the flow's data quality. This information is not required, but if provided it increases the process' usefulness. The flow data quality schema must first be defined on the ‘General information’ tab to be entered for each flow in the ‘Inputs/Outputs’ tab. It is preferred that you use the US EPA data quality schema for process flows. For details on the data quality scheme, see the pull-down menu descriptors in openLCA or the [EPA 2016 Guidance Document on Data Quality Assessment for LCI Data](https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=528687).|_(1;2;1;2;4)_|
|(M) Description|This field is required where applicable. Briefly describe the flow's relationship to the process and assumptions used to obtain the quantitative reference or data quality|_Transport to secondary processing_|

<br><br><br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)
<br><br>
[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)
<br><br><br>





  
  

# Outputs Field Conventions



[**_Return to TOC_**](../00-sub-handbook-landing.md)



[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)



This set of tables includes conventions for the following fields in this tab of openLCA:

- [Outputs](#outputs)


<br>


<a id="outputs"></a> 


## Outputs



| Field Name | Convention | Examples |

|:---:|:-----|:---------|

|(A) Flow|Flow name based on the USLCI Naming Convention (see General Information, Name Field Conventions). For general elementary flow conventions, see Rules 2-9/18 and for general product/process flow names, see Rules 12-17 of [Appendix D: ILCD Nomenclature Rules](../04-resources/04-App-D.md). See the full [ILCD Handbook](http://eplca.jrc.ec.europa.eu/uploads/MANPROJ-PR-ILCD-Handbook-Nomenclature-and-other-conventions-first-edition-ISBN-fin-v1.0-E.pdf) for detailed conventions|_Scanner; Kodak Alaris i940 desktop scanner; Global supply chain; 1 unit, 1.55 kg_|
|(A) Category|Flow category based on the USLCI Categorization Convention (see [General Information, Name Field Conventions](../field-conventions/general-info.md#general-information))|_Chemical Manufacturing/All Other Basic Inorganic Chemical Manufacturing_|
|(M) Amount|Flow quantity|_1.55_|
|(M) Unit|Flow unit; the openLCA software includes a set of unit groups and units; these units must be used to ensure proper data importation. If these units are not appropriate for one or more of your dataset flows, let your Data Curator know and NREL will assist in adding a unit to the list|_kg_|
|(O) Costs/Revenues|This field is provided for documenting life cycle costing (LCC) data; the currency and costs may be provided for each flow; the costs per unit are automatically generated based on this information and flow amount|_15 USD/unit_|
|(O) Uncertainty|Describe flow's data uncertainty. This information is not required, but if provided it increases the process' usefulness. The distribution type, mean, and standard deviation may be provided|_Normal distribution_<br>_Mean = 1.55_<br>_Standard deviation = 0.44_|
|(O) Avoided product|Used to indicate allocation has been avoided in a multi-functional process. This box should only be checked for the by-product flow(s). If the box is checked, the process avoiding the product flow must also be submitted.|_Blank_|
|(O) Data quality entry|Describe the flow's data quality. This information is not required, but if provided it increases the process' usefulness. The flow data quality schema must first be defined on the ‘General information’ tab to be entered for each flow in the ‘Inputs/Outputs’ tab. It is preferred that you use the US EPA data quality schema for process flows. For details on the data quality scheme, see the pull-down menu descriptors in openLCA or the [EPA 2016 Guidance Document on Data Quality Assessment for LCI Data](https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=528687).|_(1;2;1;2;4)_|
|(M) Description|This field is required where applicable. Briefly describe the flow's relationship to the process and assumptions used to obtain the quantitative reference or data quality|_Transport to secondary processing_|

<br><br><br>

[**_Return to TOC_**](../00-sub-handbook-landing.md)

<br><br>

[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)
<br><br><br>





  
  
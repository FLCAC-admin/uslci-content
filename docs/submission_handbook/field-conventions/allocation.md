# Allocation Field Conventions

>**NOTE:** Mandatorily Used Only with Multi-Functional Processes
<br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)

[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)

This set of tables includes conventions for the following fields in this tab of openLCA:
- [Physical & Economic Allocation](#physical-and-economic)
- [Causal Allocation](#causal)
<br>

<a id="physical-and-economic"></a>
## Physical & Economic Allocation (only for physical & economic allocation)

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(M) Default method|Pull-down menu allows designation of no method or causal, economic, or physical allocation methods for multi-functional processes|_Physical_|
|(A) Product|Is the first reference flow by default; the primary product and co-products must have the same flow property|_bark (0.3 kg)_<br>_wood (1.00 kg)_|
|(A) Physical|Allocation factors are based on the physical (e.g., mass or energy) ratio of the product flows; the ratio for the product will be 1.0 for a single-output process; for multi-output processes, the ‘Calculate default values’ button will automatically calculate the ratios based on the default (reference) flow property|_0.23076923076923075_<br>_0.7692307692307692_|
|(A) Economic|Allocation factors are based on the economic value of the product flows; the ratio of the product will be 1.0 for a single-output process; for multi-output processes, an economic flow property must first be added to each product flow; then, the ‘Calculate default values’ button will automatically calculate the ratios based on the economic value of the product flows|_0.1071428571485712_<br>_0.8928571428571428_|
<br>
<a id="causal"></a> 

## Causal Allocation (only for causual allocation)

|Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(A) Flow|Lists the process flow outputs and inputs|_Green lumber_|
|(A) Direction|Indicates whether the flow is a process input or output|_Output_|
|(A) Category|Indicates the flow category|_Forestry and logging/Logging_|
|(A) Amount|The amounts are automatically calculated given the causal allocation ratio entered in the columns to the right of the amounts (i.e., for each product/by-product); the ratios are added manually|_Bark 0.4 kg; Wood 0.6 kg for a causal ratio of 0.4 to 0.6_|

<br><br><br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)
<br><br>
[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)
<br><br><br>




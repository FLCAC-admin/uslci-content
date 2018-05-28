# Process Parameters Field Conventions

[**_Return to TOC_**](../00-sub-handbook-landing.md)

[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)

This set of tables includes conventions for the following fields in this tab of openLCA:
- [Input & Dependent Parameters](#input-and-dependent-parameters)
- [Additional Information](#additional-information)

<a id="input-and-dependent-parameters"></a> 
## Input & Dependent Parameters

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(O) Name|Parameter name. Parameter names have the following restrictions: no spaces; no special characters; no more than 255 characters|_belt_length_|
|(O) Description|Brief description of how and why the parameter was developed.|_Total conveyor belt length in meters._|
<br>


<a id="additional-information"></a> 
## Additional Information

| Field Name | Convention | Examples |
|:---:|:-----|:---------|
|(O) Amount/Value|The default numeric value for the database|_73.32_|
|(O) Uncertainty|Describe parameter's uncertainty. This information is not required, but if available and provided, increases the dataset's clarity.|_Triangle distribution_<br>Minimum = 50<br>Mode = 75<br>Maximum = 100|
|(O) Dependent Parameter Formula|Parameter formulas have the following rules:<ul><li> Operators include "+","-","*","/".</li><li>Must use the parameter names as named in the ‘Parameters’ tab or otherwise already defined as global parameters in the openLCA database navigator.</li><li>Maximum of 255 characters and no units so these should be added to the ‘Description’ field</li><li>More complex functions are possible (such as using Booleans and regular expressions), but are not documented and described here.</li><li>Additional information on parameter functions can be found in the openLCA user manual</li></ul>|_(cold_st_wt*belt_length)+tail_pulley+drive_pulley_|

<br><br><br>
[**_Return to TOC_**](../00-sub-handbook-landing.md)
<br><br>
[**Return to Metadata Guidance Tables List**](../02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)
<br><br><br>





  
  

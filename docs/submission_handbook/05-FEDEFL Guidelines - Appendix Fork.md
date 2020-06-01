# FEDEFL Nomenclature Highlights

[**_Return to TOC_**](../00-sub-handbook-landing.md)

> This section includes highlights from the FEDEFL guidance. The full guidance document can be found at
> <span class="underline"><https://cfpub.epa.gov/si/si_public_record_Report.cfm?dirEntryId=347251&Lab=NRMRL>.</span>

#### <span class="smallcaps">Highlight 1: A flow must consist of a ***Flowable*** + ***Context*** + ***Unit***</span>


>
>1. ***Flowable*** - The name of the material, energy, or space (e.g., “Carbon dioxide” or “Water, fresh”) that comes from or goes to the biosphere. This is commonly called “substance” or “flow name” but this term is too limited and the term “flowable” from the Earthster Core Ontology (ECO) is used in the FEDEFL (McBride & Norris, 2010). 
>2. ***Context*** - A set of environmental media/compartments that describe the flow origin or destination (e.g., “Air”). Although the term "compartment" is sometimes used in LCA, the FEDEFL uses the term context to provide a broader meaning that includes the directionality (e.g. “resource” from biosphere or “emission” to biosphere), environmental media (e.g. “Air”, “Water”, “Ground” and “Biotic”), and additional secondary context information that is further described in Section 3.3 of the FEDEFL report. It is mandatory that a flow have a primary context (directionality + environmental media). The FEDEFL also includes preferred flows, which further specify secondary context information such as the type of water body (e.g., lake, river) an emission is discharged to. Highlight 5 provides more detail on secondary context information.
>3. ***Unit*** - Flow units may be associated with conversion factors that can be used to convert between different units within a flow property (e.g., kg to lbs.) or even between flow properties (e.g., kg to m^3). 


#### <span class="smallcaps">Highlight 2: Elementary flow primary contexts</span>

> 
> Contexts are listed by directionality (Resource/Emission) and environmental media (Air, Ground, Water, Biotic)
> 
> **Resources**
>
>>Resource, Ground
> 
>>Resource, Water
> >
>>Resource, Air
> 
>>Resources, Biotic
>
>**Emissions**
> 
>> Emissions, Ground
> 
>>Emissions, Water
> 
>>Emissions, Air


#### <span class="smallcaps">Highlight 3: Environmental media based on phase (e.g. solid, liquid, gas, biosphere)</span>

> 
> The FEDEFL distinguishes between the environmental media and the vertical strata creating a flow context. 

>Example:
>> A resource flow from "groundwater, well" would conventionally have the flow context resource/ground. However, ground more accurately describes the vertical strata from which the resource is extracted, while the environmental media from which the resource is flowing is water. Therefore, in the FEDEFL the terms air, water and ground refer to the media, while another class is used to describe the vertical strata. It is important to note that for emission, the environmental media reflects the media the flow is going to and that for resources it is the media from which a resource originated. 

>The biotic media is used to describe the living media which some material flows from, such as the flow of wood from trees (e.g. Hardwood, Resource/Biotic).


#### <span class="smallcaps">Highlight 4: Classifying elementary flows (Eight class system)</span>

> 
> It is recommended that users utilize the eight-class system as seen below to classify all elementary flows. Usage of the flow classification system helps improve the structure used to organize flows. Flow classes are a way to group elementary flows by their flowable type. Classes may have sets of contexts and units that distinguish them from flows in other classes.
<table>
<tbody>
<tr class="odd">
<td><strong>Flow Class</strong></td>
<td><strong>Input/Output</strong></td>
<td><strong>Definition</strong></td>
<td><strong>Default flow units</strong></td>
<td><strong>Example Flowable(s)</strong></td>
</tr>
<tr class="even">
<td><strong>Element or Compound</strong></td>
<td>Both</td>
<td>A unique chemical element or compound</td>
<td>kg</td>
<td><em>1,1,2,2-Tetrachloethane</em></td>
</tr>
<tr class="odd">
<td><strong>Groups of Chemicals</strong></td>
<td>Both</td>
<td>A group or mixture of chemicals</td>
<td>kg</td>
<td><em>Volatile organic compounds</em></td>
</tr>
<tr class="even">
<td><strong>Geological</strong></td>
<td>Both</td>
<td>A mineral or metal in an ore or aggregate material extracted for use or refining</td>
<td>MJ or kg</td>
<td><em>Anthracite</em></td>
</tr>
<tr class="odd">
<td><strong>Biological</strong></td>
<td>Both</td>
<td>Input: biomass or organic matter

>
Output: biological matter (e.g. microorganisms, mites and pollen) </td>
<td>kg</td>
<td>Input

>
<em>Hardwood</em>

>
Output
>

<em>Bacillus Subtilis</em></td>
</tr>
<tr class="even">
<td><strong>Land Use</strong></td>
<td>Input</td>
<td>Land types</td>
<td>area*time</td>
<td><em>Forest</em></td>
</tr>
<tr class="odd">
<td><strong>Water</strong></td>
<td>Both</td>
<td>Water</td>
<td>kg</td>
<td><em>Water, fresh</em></td>
</tr>
<tr class="even">
<td><strong>Energy</strong></td>
<td>Both</td>
<td>Energy input NOT associated with consumed materials

>
Energy output in the form of heat</td>
<td>MJ</td>
<td>Input

>
<em>Energy, Geothermal</em>

>
Output
>
<em> Energy, heat</em></td>
</tr>
<tr class="odd">
<td><strong>Other</strong></td>
<td>Both</td>
<td>None of the above. May include water quality parameters.</td>
<td></td>
<td><em>Biological Oxygen Demand</em></td>
</tr>
</tbody>
</table>

#### <span class="smallcaps">Highlight 5: Further differentiation of context information (secondary context information)</span>

> Secondary context information provides further details. Not all secondary context information applies to each of the flow classes. Below is a complete list of all combinations of primary and secondary flow context: 
*(It is recommended that users use the appropriate context with as much specificity as possible).*
>
>
><strong>Emissions</strong>
>
>
>><strong>*Air*</strong>
>
>*emission/air,
> emission/air/indoor,
> emission/air/stratosphere,
> emission/air/subterranean,
> emission/air/troposphere/ground-level,
> emission/air/troposphere/high,
> emission/air/troposphere/low,
> emission/air/troposphere/rural,
> emission/air/troposphere/rural/ground-level,
> emission/air/troposphere/rural/high,
> emission/air/troposphere/rural/low,
> emission/air/troposphere/urban,
> emission/air/troposphere/urban/ground-level,
> emission/air/troposphere/urban/high,
> emission/air/troposphere/urban/low,
> emission/air/troposphere/very high*
>
>><strong>*Ground*</strong>
>
>*emission/ground
> emission/ground/human-dominated,
> emission/ground/human-dominated/agricultural,
> emission/ground/human-dominated/agricultural/rural,
> emission/ground/human-dominated/agricultural/urban,
> emission/ground/human-dominated/commercial,
> emission/ground/human-dominated/commercial/urban,
> emission/ground/human-dominated/commercial/rural,
> emission/ground/human-dominated/industrial,
> emission/ground/human-dominated/industrial/rural,
> emission/ground/human-dominated/industrial/urban,
> emission/ground/human-dominated/residential,
> emission/ground/human-dominated/residential/rural,
> emission/ground/human-dominated/residential/urban,
> emission/ground/subterranean,
> emission/ground/terrestrial/barren land,
> emission/ground/terrestrial/forest,
> emission/ground/terrestrial/grassland,
> emission/ground/terrestrial/shurbland,
> emission/ground/terrestrial/snow and ice,
> emission/ground/terrestrial/wetland*
>
>><strong>*Water*</strong>
>
>*emission/water
> emission/water/brackish water body,
> emission/water/brackish water body/lake,
> emission/water/brackish water body/lake/rural,
> emission/water/brackish water body/lake/urban,
> emission/water/fresh water body,
> emission/water/fresh water body/lake,
> emission/water/fresh water body/lake/rural,
> emission/water/fresh water body/lake/urban,
> emission/water/fresh water body/river,
> emission/water/fresh water body/urban,
> emission/water/saline water body,
> emission/water/saline water body/ ocean,
> emission/water/subterranean,
> emission/water/subterranean/brackish water body,
> emission/water/subterranean/brackish water body/confined aquifer,
> emission/water/subterranean/brackish water body/unconfined aquifer,
> emission/water/subterranean/fresh water body,
> emission/water/subterranean/fresh water body/confined aquifer,
> emission/water/subterranean/fresh water body/ unconfined aquifer,
> emission/water/subterranean/saline water body,
> emission/water/subterranean/saline water body/ confined aquifer,
> emission/water/subterranean/saline water body/unconfined aquifer*
>
><strong>Resources</strong>
>
>><strong>*Air*</strong>
>
>*resource/air
>resource/air/subterranean
>resource/air/troposphere*
>
>><strong>*Biotic*</strong>
>
>*resource/biotic*
>
>><strong>*Ground*</strong>
>
>*resource/ground
> resource/ground/human-dominated,
> resource/ground/human-dominated/agricultural,
> resource/ground/human-dominated/agricultural/rural,
> resource/ground/human-dominated/agricultural/urban,
> resource/ground/human-dominated/commercial,
> resource/ground/human-dominated/commercial/rural,
> resource/ground/human-dominated/commercial/urban,
> resource/ground/human-dominated/residential,
> resource/ground/human-dominated/residential/rural,
> resource/ground/human-dominated/residential/urban,
> resource/ground/human-dominated/rural,
> resource/ground/human-dominated/urban,
> resource/ground/subterranean,
> resource/ground/terrestrial/barren land,
> resource/ground/terrestrial/forest,
> resource/ground/terrestrial/grassland,
> resource/ground/terrestrial/shrubland,
> resource/ground/terrestrial/snow and ice,
> resource/ground/terrestrial/wetland*
>
>><strong>*Water*</strong>
>
>*resource/water
> resource/water/brackish water body,
> resource/water/brackish water body/lake,
> resource/water/brackish water body/lake/rural,
> resource/water/brackish water body/lake/urban,
> resource/water/fresh water body,
> resource/water/fresh water body/lake,
> resource/water/fresh water body/lake/rural,
> resource/water/fresh water body/lake/urban,
> resource/water/saline water body,
> resource/water/saline water body/ocean,
> resource/water/subterranean,
> resource/water/subterranean/brackish water body,
> resource/water/subterranean/brackish water body/confined aquifer,
> resource/water/subterranean/brackish water body/unconfined aquifer,
> resource/water/subterranean/fresh water body,
> resource/water/subterranean/fresh water body/confined aquifer,
> resource/water/subterranean/fresh water body/unconfined aquifer,
> resource/water/subterranean/saline water body,
> resource/water/subterranean/saline water body/confined aquifer,
> resource/water/subterranean/saline water body/unconfined aquifer*

#### <span class="smallcaps">Highlight 6: Alternative units</span>


#### 



> Some flows can be used with different units, e.g. radioactive chemicals can use the ‘kg’ or ‘kBq’ units. In instances where multiple units are possible, one unit is set as the FEDEFL default unit and other units are considered alternative units. All flows with an alternative unit exist within the AltUnit files on [github](https://github.com/USEPA/Federal-LCA-Commons-Elementary-Flow-List/tree/master/fedelemflowlist/input) by flow class (see example below).

>![](./media/Altunits.png)
>
>Alternate units exist using a conversion factor between the different unit types. For each alternate unit there is a single default conversion factor. When mapping flows from an existing source to the FEDEFL users may input their own conversion factors.
 
>><strong>Example</strong>:
>When converting flow names from an existing source, if the source contains conversion factors in the name (e.g. “Hard coal; 32.7 MJ/kg” and the units do not match the default units in the FEDEFL then users should use 32.7 MJ/kg as a conversion factor in the mapping file. However, there is no need to input a conversion factor in the mapping file when the units match the default units in FEDEFL.

#### <span class="smallcaps">Highlight 7: Geological ‘fuel’ flows, how to use alternative units and account for energy losses</span>

> 
> In general, when creating flows to represent the extraction of raw resources, it is recommended that the name of the raw material being extracted be used. For raw material that is used to produce energy (e.g. fuels), it is important to note that in the FEDEFL there exists default conversion factors (higher heating values (HHV)) to convert the ‘kg’ of raw resource into an energy content. Users <strong>should</strong> apply an increase (e.g., 5-10%) in their Cumulative Energy Demand (CED) during refining to address the energy loss from the raw material to the refined material for all non-renewable fuels. 
> 

#### <span class="smallcaps">Highlight 8: Minerals, metals and ores</span>

> 
> When modeling geological flows, the raw resource, or mineral names should be used as the elementary flow flowable. The reason for this recommendation is that this method requires users to track flows through the technosphere transformations to create the metals that are used during manufacturing. Mining metals, gangue or excess rock and non-valuable products as well as trace elements/metals are part of the initial raw resource extraction process. By modeling the raw material mineral, users can account for these by-products in the refining process. 
However, in some instances this is not possible as users may not know this information. Therefore, metals as raw resources are still included in the ‘Geological’ flow class. Users should be careful when using these flows that they account for the raw material losses from extraction through refining. It is recommended that users apply a loss of material (e.g., 5-10%) during refining when back-calculating the input quantity of the raw material.

> 
#### <span class="smallcaps">Highlight 9: Land use</span>

> 
>Land transformations are not included as elementary flows in the FEDEFL. Transformations are an activity and should be modeled as a process with land inputs. Only land occupations are elementary flows in the FEDEFL and are named based on the land types. All land occupation should have units of area*time. Any land flows that do not have such units are not in compliance with FEDEFL nomenclature.  
#### 

#### <span class="smallcaps">Highlight 10: Identifying and formatting ‘Element or Compound’s and ‘Groups of Chemicals’</span>

> 
> All ‘Element or Compound’s and ‘Groups of Chemicals’ are identified using the [US EPA Substance Registry Services (SRS)](https://ofmpub.epa.gov/sor_internet/registry/substreg/home/overview/home.do) and [US EPA Chemistry Dashboard](https://comptox.epa.gov/dashboard). No ‘Element or Compound’ or ‘Groups of Chemicals’ flowables may be added to the FEDEFL without some type of identification found in either of the two databases. At this time, formatting of the ‘Element or Compound’ and ‘Groups of Chemicals’ flowables reflects the formatting found in SRS and Chemistry dashboard. 

><strong>Ions</strong>
>
>>Ions should be named using the numerical numbers to identify the ion. Below are some examples of the appropriate nomenclature for ions.

>*Examples*:
>
>>Chromium(IV), Vanadium(V), Barium(II), Tin(II)

><strong>Radioactive elements</strong>
>
>>Radioactive elements should include the numerical value of the isotope. 

>*Examples*:
>
>>Antimony-125, Radon-222

><strong>Abbreviations should be avoided.</strong>
>
>
><strong>Naming of chemicals in combination should be avoided.</strong>
>
>>When mapping, it is better to estimate the conversion factor for each chemical and name a chemical as an individual speciated chemical rather than by chemical group or in combination. This improves the connection between LCI data and LCIA characterization factors and will yield more accurate results. 

>*Example*
>
>>'Dioxins and Furans' should now be two flows 'Dioxins' and 'Furans'

#### 

#### <span class="smallcaps">Highlight 11: Water flows</span>

> 
><strong>Assigning fresh, brackish and saline </strong>
>>Whenever possible, users should include the salinity of water flowables. The FEDEFL does include the generic term Water for use when mapping sources that do not specify the salinity. Context information should be used to capture additional information such as water body type and environmental media. 
<table>
<tbody>
<tr class="odd">
<td><strong>Example Water Flowable</strong></td>
<td><strong>FEDEFL Flowable</strong></td>
<td><strong>FEDEFL context</strong></td>
</tr>
<tr class="even">
<td>Rainwater</td>
<td>Water,fresh</td>
<td>resource/air*</td>
</tr>
<tr class="odd">
<td>Water, ocean</td>
<td>Water, saline</td>
<td>resource/water/saline water body/ocean</td>
</tr>
<tr class="even">
<td>Water emission to freshwater lake</td>
<td>Water**</td>
<td>emission/water/fresh water body/lake</td>
</tr>
</tbody>
</table>

>>*It is recommended that rainwater be named 'Water, fresh' and be a resource from air. Rainwater should only be describing the flow of water from the atmosphere into a rainwater collection systems. Rainwater flowing from a collection system is a technosphere flow as it is NOT flowing directly from the biosphere.
>
>>**When the original source flow does not provide enough detail; the generic term, in this case 'Water' can be used when naming the flow even though this is not a preferred FEDEFL term.

><strong>Water quality parameters</strong>
>>Water quality parameters like Chemical/Biological Oxygen Demand are classified under the ‘Other’ elementary flow class. Additional quality parameters like pH are measured using the flowable ‘Hydrogen ion’ because the source reporting is in H+ units. This flow is found in the ‘Element or Compound’ flow class. 
#### <span class="smallcaps">Highlight 12: Location specific data</span>

>
>There is no need to include locations in the naming of flowables since this information can be captured as part of the exchange metadata. An exchange is defined as a flowable used in a process with specific situational metadata included to describe the flowable.
<strong>Example:</strong>
>When a ‘Particulate Matter, <2.5µm’ flowable is used in process to describe the total particulate matter in ‘kg’ emissions to air from coal power plant in Kentucky, USA from January 1, 2019 – December 31, 2019. The flowable takes on the additional context information of an emission to air and units ‘kg’ to become a unique flow. The additional metadata of being from a specific process (e.g., coal power plant) at a specific location (e.g., Kentucky, USA) from a specific time period (e.g., 2019) is part of the exchange. The additional location, time period and process are not part of the FEDEFL nomenclature, but additional metadata to describe the use of this flowable.

#### <span class="smallcaps">Highlight 13: “Biogenic and fossil gases (e.g. methane and carbon dioxide) ” field</span>

> 
>The FEDEFL nomenclature is founded on the principle that flowables are unique substances. Therefore, when dealing with biogenic or fossil gases the flowables it is recommended not to include these terms. Biogenic carbon dioxide is chemically identical to carbon dioxide and therefore <strong>NOT</strong> a unique substance. 

>Currently, naming gases as biogenic is used as a modelling and accounting workaround for LCA. Since the FEDEFL recommends that users do not distinguish biogenic gases, the FEDEFL recommends the following method for ensuring that biogenic gases are accounted for correctly.   A basic rule is to have the gas (e.g., Carbon dioxide) with the context resource/air to account for any uptake. Users should then add a -1 characterization factor (e.g., kg CO2 equivalent/kg) to the GHG LCIA method for this flow to account for this uptake, which will cancel out the “biogenic CO2” emissions. 
#### 

#### <span class="smallcaps">Highlight 14: End-of-life waste </span>

>While end-of-life waste flows are technically flows back to the biosphere, they are classified differently than elementary flows and not included in the FEDEFL. Waste sent for further processing or management (e.g., to landfill, incineration) should be considered technosphere flows. Whenever possible, it is recommended that final waste released to the biosphere be characterized by the 'Element or Compound' or 'Groups of Chemicals' so that flows can be characterized in LCIA methods. When specifics are not possible, it is recommended that users use the ILCD format for waste flows in naming End of life waste. 

[**_Return to TOC_**](../00-sub-handbook-landing.md)

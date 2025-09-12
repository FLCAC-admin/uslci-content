**To prepare WARM v16 processes for use in USLCI the following steps were taken:**
- Converted the waste modeling methodology to the material flow logic.
  - Processes are now waste treatment processes with a waste flow on the inputs as opposed to a standard unit process with a product flow on the outputs.
- Flow mapped elementary flows to FEDEFL.
  - See the mapping file [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/WARM/WARM%20flow%20mappings.csv).
  - Converted the carbon resource/ground to a negative carbon dioxide emission flow so that it will be captured in LCIA methods outside of those developed for WARM.
  - Economic flows could not be mapped. Evaluated mapping these flows to the USEEIO economic flows but decided not to because of minor differences in scope (e.g., taxes vs taxes on production and imports, less subsidies). May update these flows in the future to be compatible with USEEIO.
- Flow mapped technosphere flows to USLCI and eLCI
  - See the mapping file [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/WARM/WARM%20flow%20mappings.csv).
  - Referenced WARM background documentation for transport modes and fuel types to appropriately map these flows.
  - Note that the steel recycling flow referenced in the Mixed MSW combustion is currently a cut-off flow and does not account for avoided steel production. This does not have a significant affect on the LCIA results.
- Converted global parameters to process parameters and created new unit conversion process parameters.
- Added metadata.
- Corrected errors.
  - Removed subtraction of combustion MSW transport distance.
  - Added ash transport distance which corrected error related to the original emission factor.
  - Fixed validation errors related to internalIDs, flow properties, and allocation.
  - Various minor corrections (e.g., assigning missing providers and grammatical fixes).

A results comparison between WARM v16 zolca format and the adapted USLCI version can be found [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/WARM/WARM%20Results%20Comparison%20GWP.xlsx).

Multiple existing USLCI landfill and combustion flows were mapped to the new WARM flows. These mappings can be found [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/WARM/Cutoff%20flows%20to%20WARM%20mappings.xlsx).

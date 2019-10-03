# USLCI Change Log

[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

<br>



This change log contains a summary of changes to the [U.S. Life Cycle Inventory Database (USLCI)](https://uslci.lcacommons.gov/).  The USLCI is updated quarterly based on the [U.S. Federal Government Fiscal Calendar](https://www.senate.gov/reference/glossary_term/fiscal_year.htm).
<br><br>



###### Table 1. USLCI Change Log

| **Release** | **File Type** | **Change Type** | **File Name** | **UUID** | **Description** |
| --- | --- | --- | --- | --- | --- |
| FY19.Q3.01 | All technospheric flows | Folder &amp; Flow Re-categorization | All technospheric processes and product flows |  ~ 5,000 flows (UUIDs not changed with re-categorization) | Transitioned to using the Federal LCA Commons Core (&quot;Starter&quot;) Database with the NAICS Folder Structure &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| FY19.Q3.01 | Product | Folder arrangement | CUTOFFs Folder | ~ 670 flows (UUIDs not changed with folder rearrangement) | Moved CUTOFF folder to &quot;Technosphere Flows&quot; folder under &quot;Flows&quot; |
| FY19.Q3.01 | Products | Nomenclature | Flows/Technosphere Flows | ~ 1,000 flows (UUIDs not changed with nomenclature changes) | Primarily agricultural, utilities, and transport products decoupled from their parent processes to eliminate geographic and temporal specificity from the product flow name and eliminate duplicate flows; a default provider may now be selected for products with more than one parent process |
| FY19.Q3.01 | Indicators &amp; Parameters/Data Quality Systems | Addition | US EPA - Flow Pedigree Matrix | d13b2bc4-5e84-4cc8-a6be-9101ebb252ff | Transitioned to using the Federal LCA Commons Core (&quot;Starter&quot;) Database with the EPA Data Quality System |
| FY19.Q3.01 | Indicators &amp; Parameters/Data Quality Systems | Addition | US EPA - Process Pedigree Matrix | 70bf370f-9912-4ec1-baa3-fbd4eaf85a10 | Transitioned to using the Federal LCA Commons Core (&quot;Starter&quot;) Database with the EPA Data Quality System |
| FY19.Q3.01 | Process | Edit | Diesel, combusted in industrial boiler | 53804132-4bd6-3b18-bfbd-14ac762431ef | Corrected CO2 emission factor for volume (m3) basis of diesel combustion (from 2.272 kg/m3 to 2.272e3 kg/m3) |
| FY19.Q3.01 | Process | Addition | Scanner, desktop, E1025, E1035, S2040, S2050, S2060w, S2070, S2080w, at plant | 42975a63-8c39-4d46-8b6b-34d9a7174295 | Added updated scanner model production processes per provider |
| FY19.Q3.01 | Process | Deletion | Scanner, i1150WN desktop | f37e9da9-59f6-3c97-ac78-faab05ccd0c6 | Deleted outdated model dataset (no longer in production) per provider |
| FY19.Q3.01 | Process | Deletion | Scanner, i1190E desktop | f3c0b490-e642-31d7-8793-b6ff5e311b13 | Deleted outdated model dataset (no longer in production) per provider |
| FY19.Q3.01 | Process | Deletion | Scanner, i1190WN desktop | f74d08fc-3834-3e73-9d20-ca3b4413cb88 | Deleted outdated model dataset (no longer in production) per provider |
| FY19.Q3.01 | Product | Units &amp; Reference Flows | Natural gas, processed, at plant | 5346e475-e7c4-38bf-b1b7-8c23549d2081 | Inserted quantitative flow properties in flow name and unit conversion factor to switch between mass and volume basis (0.7369 kg/m3 and 1.357 m3/kg) |
| FY19.Q3.01 | Product | Units &amp; Reference Flows | Natural gas, processed, at plant | bd83ce23-816f-3589-b25f-dfca03b42932 | Inserted quantitative flow properties in flow name and unit conversion factor to switch between mass and volume basis (0.7369 kg/m3 and 1.357 m3/kg) |
| FY19.Q3.01 | Product | Units &amp; Reference Flows | Natural gas, at extraction site | 93c1e14e-c021-3b1d-bcd7-ed9ad3404689 | Inserted quantitative flow properties in flow name and unit conversion factor to switch between mass and volume basis (0.7369 kg/m3 and 1.357 m3/kg) |
| FY19.Q3.01 | Product | Units &amp; Reference Flows | Natural gas, extracted | f8f274bf-d047-3676-be1a-753ba2f6f965 | Inserted quantitative flow properties in flow name and unit conversion factor to switch between mass and volume basis (0.7369 kg/m3 and 1.357 m3/kg) |
| FY19.Q3.01 | Product | Units &amp; Reference Flows | Natural gas, combusted in industrial equipment | 720ef590-2596-382a-998f-62d1d0f6afc6 | Inserted quantitative flow properties in flow name and unit conversion factor to switch between mass and energy basis (52.13 MJ/kg and 0.019 kg/MJ) |
| FY19.Q3.01 | Process | Weight factor edit | Biodegradable loose fill | c139b46e-e0c1-3be5-ad3d-451d6392bad6 | Original weight factor for input of natural gas combusted at industrial equipment provided by data submitter was 0.76472 MJ; converted to link to USLCI combustion process on m3 basis using higher heating value and density 52.13 MJ/kg and 0.7369 kg/m3, respectively. |
| FY19.Q3.01 | Product | Deletion | Natural gas, combusted in industrial equipment | 720ef590-2596-382a-998f-62d1d0f6afc6 | Product on energy basis not linked to parent process; deleted and added conversion factor to units of equivalent flow on volume basis linked to parent process |
| FY19.Q3.01 | Process | Re-categorization | Harvesting, fresh fruit bunch, at farm, 2003 | 0375c701-8d66-3b47-af2e-26b0c43c722f | Re-categorized to 1113: Fruit and Tree Nut Farming |
| FY19.Q3.01 | Product | Edit | Harvesting, fresh fruit bunch, at farm | 9dfc9e7c-3c20-3f4d-9d79-d54ec2d8d08b | Set as quantitative reference for process &quot;Harvesting, fresh fruit bunch, at farm, 2003&quot; so as to link to palm kernel production process (repaired broken link) |
| FY19.Q3.01 | Process | Addition | Ethylene glycol, materials production, organic compound, at plant, kg | 2a78de43-fdf2-4c5f-b527-89db6568ace8 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Ethylene, materials production, organic compound, at plant, kg | 520ecb54-7b55-42ca-97c3-4b8192189356 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Methanol, at plant, kg | 6b0d74c7-e880-4b93-aa2f-b777ac183f84 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Process | Addition | Paraxylene, at plant, kg | d32a7e23-c6c0-400a-8134-656a3e13c11f | PET data update supply chain; replace older version |
| FY19.Q3.01 | Process | Addition | Polyethylene terephthalate (PET) virgin resin, at plant, kg | 2b2f738d-2044-462f-ba56-5112ee683cb6 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Purified terephthalic acid (PTA), at plant, kg | e893cef4-aab1-4b77-944d-1dc4f669419a | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Xylenes, mixed, produced from naphtha, at plant, kg | 9fcf5696-e172-42da-a010-e8d577e2bbd7 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Process | Addition | Natural gas, at processing, conventional, kg | 8dcef86f-cf2c-4207-91aa-1398401fe8b7 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at processing, production mixture, to consumer, kg | ee8077d4-d28c-46c4-9f15-5b22bce6063d | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at processing, shale, kg | 7bfdfa88-b857-4a4a-bbb9-3f51ddc15d30 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, Barnett Shale, kg | e7425edd-537c-497f-aa4b-7a8a79b1ab4a | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, coal bed methane, kg | 0945cc82-1126-45c3-b525-6d4fc913aa09 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, conventional offshore, kg | bc4c2bad-4bdb-4402-8aed-74efc5781057 | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, conventional onshore associated, kg | 7ae49a74-3d24-4b32-ae19-ddbf6e0ae94a | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, conventional onshore, kg | f2996639-3901-4d02-8046-4e647947b7cb | PET data update supply chain |
| FY19.Q3.01 | Process | Addition | Natural gas, at extraction, production mixture, to consumer, kg | 058ef703-9452-44a8-84e6-d14551e61713 | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Ethylene glycol, at plant, kg | a5c7d642-4e3a-40af-a919-a2f7601340b0 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Ethylene, at plant, kg | ec1bf0d1-ff71-4960-aa0f-9fc87c14f972 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Methanol, at plant, kg | ae69b712-d8d2-41ef-a2c1-fb477807f742 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Paraxylene, at plant, kg | 44067793-674b-441e-b898-369f32f99ba0 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Polyethylene terephthalate (PET) virgin resin, at plant, kg | e7bbbd06-5887-45b0-a3c2-c9d06d571351 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Purified terephthalic acid (PTA), at plant, kg | e44db792-600e-4b75-af39-c3c094899e9e | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Xylenes, mixed, at plant, kg | 77abdac3-53ca-4ee2-be95-3b3686c3e556 | PET data update supply chain; replace older version |
| FY19.Q3.01 | Product | Addition | Natural gas, at processing, conventional, kg | 7445d544-fd68-4cb8-9f75-00428a6b4c98 | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at processing, composite, kg | 1a30ee75-215c-47ab-8927-8d15cdf63407 | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at processing, shale, kg | 5fad297f-057e-468c-8ae1-bd4ef37514f3 | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, Barnett Shale, kg | 43ab3de2-e1a2-4e1a-9613-68e9cbd7aab5 | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, coal bed methane, kg | 1d674722-7562-4360-8677-93bf36a9a57a | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, conventional offshore, kg | fdfa1dbf-3593-45ff-b0dc-6b3f9d8fa4bd | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, conventional onshore associated, kg | 4398eda3-a9ac-444b-bc90-0e042335fa2f | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, conventional onshore, kg | f1deade7-12b4-45c8-a00f-946a33de6d2c | PET data update supply chain |
| FY19.Q3.01 | Product | Addition | Natural gas, at extraction, composite, kg | c1618370-1fc6-45fc-a2cc-2458bc9ddf6a | PET data update supply chain |
| FY19.Q3.01 | Process | Deletion | Polyethylene terephthalate, resin, at plant, CTR | e4822728-95ae-3360-9870-c363a214611e | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Deletion | Methanol, at plant | 1e5b1ac8-2464-394e-b20b-b5753fe3ebfb | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Deletion | Ethylene glycol, at plant | 71f1affd-f714-35df-8899-bd516a989f2a | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Deletion | Ethylene, at plant | 15761bf7-4eff-374b-b9e7-b44b790cc939 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Deletion | Paraxylene, at plant | abb55ad3-70d1-3e05-8408-d657fb9c3feb | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Deletion | Xylenes, mixed, at plant | 182abb98-80e5-3218-9474-ccacb504f7b4 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Polyethylene terephthalate, resin, at plant, CTR | 749ccf4c-514f-35fc-ad76-8cde2b3800e6 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Methanol, at plant | 0a086de3-ddb0-3c48-b5db-2f36f5322de4 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Ethylene glycol, at plant | 4dbab98f-d541-3140-886d-3b4aaaa3e749 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Ethylene, at plant | 8a2f201e-cf8a-3017-9247-a4f98b9e1aba | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Paraxylene, at plant | 491f0bfc-bb41-3b04-8e84-6628c2b42211 | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Product | Deletion | Xylenes, mixed, at plant | ddf8108d-b0fd-3b97-b3dd-fab7d66e73fc | PET data update supply chain; replaced by newer version |
| FY19.Q3.01 | Process | Rename | Acrylonitrile-butadiene-styrene copolymer resin, at plant, CTR | 0e42a306-ee2d-362e-8bc3-580000096459 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Methylene diphenyl diisocyanate resin, at plant, CTR | d1bf60a0-272b-3ef0-951c-7febc0546d58 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyethylene terephthalate, resin, at plant, CTR | e4822728-95ae-3360-9870-c363a214611e | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyethylene, high density, resin, at plant, CTR | ce38752e-c414-3175-9482-ce663a909a0c | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyethylene, linear low density, resin, at plant, CTR | 9bdfa7ed-cc24-3b65-9fdf-7d7e62b3c007 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyethylene, low density, resin, at plant, CTR | ba5df01a-626b-35b8-859f-f1df42dd54a0 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyol ether, for flexible foam polyurethane production, at plant, CTR | 44a82a4a-95fd-3c31-9829-cf0763dd3a93 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyol ether, for rigid foam polyurethane production, at plant, CTR | 7095d0dc-7ae2-3d72-845e-9158ad075fc1 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polypropylene, resin, at plant, CTR | 8e32a674-5963-374d-92d1-466e2c78c91b | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polystyrene, general purpose, at plant, CTR | 13821cca-f344-37b9-a367-0467be778061 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polystyrene, high impact, resin, at plant, CTR | d1c572b0-c244-3193-81fb-3a64bfb13e4d | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Polyvinyl chloride, resin, at plant, CTR | cfcb6755-e408-30e7-9ab6-165de9b7d11d | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Rename | Toluene diisocyanate, at plant, CTR | 6f2532e9-d9c0-368e-89a2-0bd48adb4dab | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Acrylonitrile-butadiene-styrene copolymer resin, at plant, CTR | fa5304ba-de40-35cf-a5d6-3e09d9b79205 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyethylene terephthalate, resin, at plant, CTR | 749ccf4c-514f-35fc-ad76-8cde2b3800e6 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyethylene, high density, resin, at plant, CTR | fa2aabaa-cfb7-3ee7-b7b1-606d681ff15a | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyethylene, linear low density, resin, at plant, CTR | 7a62c88b-00ba-36a0-8a4a-137367f3e282 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyethylene, low density, resin, at plant, CTR | 0debe6c9-212b-3dda-9705-b0e78efe7161 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyol ether, for flexible foam polyurethane production, at plant, CTR | 4ac24077-b1ac-38ac-8d0d-ef1e772ede6e | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyol ether, for rigid foam polyurethane production, at plant, CTR | e788cf0b-9dbd-341c-9ab2-5a80db504bc0 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polypropylene, resin, at plant, CTR | d0477b6a-115f-350d-bbb4-7f62243e3476 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polystyrene, general purpose, at plant, CTR | 67b50031-6239-3514-a37f-2b17de803c88 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polystyrene, high impact, resin, at plant, CTR | 53cf5851-1608-3f85-8846-d15fceeb2de6 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Polyvinyl chloride, resin, at plant, CTR | 2bb0cd6b-941b-38da-856c-1b7bd0cc5f49 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Acrylonitrile-butadiene-styrene copolymer, CTR | 3fd51bef-11d1-3d1e-9d4e-a87a90c84ad4 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Methylene diphenyl diisocyanate, CTR | 587505fb-842d-36c8-8db9-7bfad6604d7d | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyethylene terephthalate, resin, at plant, CTR | 2f9b8af0-b405-398b-bb94-9ab047bee0da | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyethylene, high density, resin, at plant, CTR | f5a4155f-114c-3801-8d37-23c987ad4276 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyethylene, linear low density, resin, at plant, CTR | 0e83b215-99fa-3f94-ab49-bb24a80646f1 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyethylene, low density, resin, at plant, CTR | 6c95730e-8ec5-33b1-8640-823faea28ee7 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyol ether, for flexible foam polyurethane production, at plant, CTR | 31acefd1-bc9d-3a41-9e87-7feea920ebe4 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polyol ether, for rigid foam polyurethane production, at plant, CTR | e13ff3f2-a570-31c8-8355-a6e31eb92ed8 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polypropylene, resin, at plant, CTR | a1d2e797-42e7-320e-a983-33a2c9a8f130 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polystyrene, general purpose, at plant | a3681e5b-b93b-3ef9-8b89-c5d43aa633d4 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polystyrene, general purpose, at plant, CTR | a3681e5b-b93b-3ef9-8b89-c5d43aa633d4 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Polystyrene, high impact, resin, at plant, CTR | bee22be9-1957-3ddb-ab6c-410f02d1151c | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for Toluene diisocyanate, CTR | ad741625-2a7e-3bda-86b3-607fb3314d76 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for polyvinyl chloride, CTR | e54f97a9-bc6a-38e3-a2e2-1c438686229a | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Toluene diisocyanate, at plant, CTR | 178c0a07-27f6-3f39-94cd-dc10874c8560 | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Product | Rename | Recovered energy, for ethylene glycol | 2f7fd020-d9d5-325d-9507-cbd74095c98f | Remove &quot;CTR&quot; from name |
| FY19.Q3.01 | Process | Deletion | Blasthole drill; Manufacture; For surface coal mine, at plant | 6fb1fcd5-2eab-4e77-9f47-7a557526bb0a | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal cleaning facility; Construction; At mine | 61122645-ec94-414f-b4b2-3be671493468 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal; Cleaned; Underground mine | ef39cdc1-cf56-45ba-ba5d-5db23349ddea | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal conveyor system; Manufacture; For surface mine, at point-of-sale; 1.83 m belt width | e129b46a-1bd6-4c01-86e3-691913791a63 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal conveyor system; Manufacture; For underground mine, at point-of-sale; 1.22 m belt width | 0e491220-fa68-4470-895b-bbb192d74464 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal crusher facility; Construction; At underground mine | cb09cf38-4b97-4374-b526-72d02a7ab8e1 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal extraction; Surface mine | 93d8ea2e-7a50-4fb3-a3b5-cf489aa1937d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal extraction; Underground mine | 4b4db9ff-6ce1-4b10-9353-baae83afbee1 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal handling; Underground mine | cbc64321-512c-4b49-9d28-ed656d6aa8e6 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal loading silo; Manufacture; For railcar loading of coal, surface mine | 88786c28-01e8-4081-ad0c-6f8d96d2e762 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal loading silo; Manufacture; For railcar loading of coal, underground mine; 295 metric tonnes | 0c67fb99-7448-4b05-95c0-f46d9bc2b846 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine commissioning and decommissioning; Production mix, surface mine | abb7efb5-29a4-4d4d-a65f-da1c7c201596 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine commissioning and decommissioning; Production mix, underground mine | be7ff3dc-e1b2-4ba3-ade0-5ffb61c7aeb2 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine equipment assembly; Production mix, surface mine | 2a658145-f087-4bbb-a8b2-2db697036e48 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine equipment assembly; Production mix, underground mine | 81ba51cf-3b37-4848-93c4-e479dd692492 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine methane emissions; Production mix, surface mine | f123ab4d-58d5-4f26-a534-ba028c557810 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine methane emissions; Production mix, underground mine | 77c9afda-47ba-4e8b-8035-1d627ea8cdcd | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine site construction; Concrete structures and asphalt paving; Underground mine | 080b02eb-1b7b-4373-8db5-57c61e3cc0ed | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine tailings storage and disposal; Production mix, underground mine | 90e6ea39-1ed4-32bc-9b03-0129c6d5b2f0 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine ventilation energy; Electric fan; Underground mine | b60ebee1-54b0-4312-9ffa-46bfe46da506 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine water use and quality; Surface mine | 5b7f889a-84d1-3e4d-9dd1-367c58f8a343 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal mine water use and quality; Underground mine | c538e2f7-e50b-4318-83e0-44203e929fff | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal preparation facility; Multiple processes; Underground mine | 8e291d54-28c6-4f4c-9ab8-ad510ec4431e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal shuttle car; Manufacture; For underground mine, at plant; 28.6 metric tonnes | 5d00446b-12c1-4bcc-8fc5-30989621ccb6 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal; Cleaned; Underground mine | ef39cdc1-cf56-45ba-ba5d-5db23349ddea | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Land reclamation; Surface coal mine | 20892605-0ac1-45a8-847b-e2fa4dbfe317 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Overburden removal; Surface coal mine | aa97565f-fae9-476e-9790-b8009afc55ae | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Wastewater treatment plant; Construction; For underground coal mine | d6a0e192-366a-4f04-bd8a-e504c97fc991 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Diesel consumption; Diesel fired equipment; Variable power rating | ad2939d6-4b37-317b-a483-264a67266e22 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Stainless steel; Manufacture; Production mix, at plant; 316 2B, 80% recycled | c19569ac-f0ab-453a-b70b-43f73bad11f8 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Steel plate; Blast furnace route; Production mix; 85% recovery rate | e0243fb9-6002-447c-b878-ac90d826c22e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Steel reinforcement bar; Blast furnace route; Production mix | 91150a40-c29d-4eff-891b-0e3fd56df1a4 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Coal stockpile stacker;  Manufacture; At point-of-sale | 92634c79-3ac0-4119-88fa-57dfbecffabc | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Continuous coal miner; Manufacture; At underground mine; 563 kW | 4d8aed7f-9f6b-48d1-bdac-cee6d83bbd35 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Dragline; Manufacture; For surface coal mine, at plant; 7,439 metric tonne working weight | 27cbb14e-8752-4acf-8e0a-56aa835f8bf9 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Electric head drive; Manufacture; For underground coal mine, at plant | 5492bd04-0aa4-4885-aaa4-3257e10a5982 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Electric shearer; Manufacture; For underground coal mine, at plant | 06485ad7-74a9-426c-a1fb-1eab9e33630e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Electric shovel; Manufacture; For surface coal mine, at plant; 109 metric tonne payload | 021e73fc-a306-486b-90a0-eaa5b3d0508b | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Electric stage loader; Manufacture; For underground coal mine, at plant | 5fe5e137-8172-48c7-9807-708c90121236 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Electric tail drive; Manufacture; For underground coal mine, at plant | 828f7d75-d8c9-4453-8a31-1d10b4b4f0c2 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Hydraulic shield; Manufacture; For underground coal mine, at plant; 2 m width | 0de15d06-983f-4c9c-a2b9-b6ba9aa23321 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Line pan; Manufacture; For underground coal mine, at plant | 062fd31a-656e-4bad-b0ca-4900def6fdf0 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Longwall mining system; Equipment assembly; Production mix, at underground coal mine | 33072bbf-19ee-4ed6-a1eb-b9ad5c4d0d97 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Mining truck; Manufacture; For surface mine, at plant; Gross machine operating weight  623,690 kg | f1563b1d-c258-4ad0-ae06-5ecfe64aeca9 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Track loader; Manufacture; At point-of-sale; 178 kW | e39e94cf-3a34-451f-82e7-f8b80a6dd77c | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Process | Deletion | Tractor-propelled coal crusher;  Manufacture; For surface mine, at plant | d259de7d-4357-45cd-ba22-76c0b5daebfc | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Blasthole drill; Manufacture; For surface coal mine, at plant | d9bc10e1-3bf6-4b60-9baf-6c595e21d041 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal cleaning facility; Construction; At mine | cf767556-0b2e-4f29-ad94-fefe2093ff92 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal; Cleaned; Underground mine | 756647e7-8bf4-49d8-9190-7d9cf39a2345 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal conveyor system; Manufacture; For surface mine, at point-of-sale; 1.83 m belt width | b4aa8250-95e3-4360-89f8-d77f8779c2f3 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal conveyor system; Manufacture; For underground mine, at point-of-sale; 1.22 m belt width | f50c5b7f-83e7-4ffe-bfd5-146c371d0b85 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal crusher facility; Construction; At underground mine | 0173c586-8af2-4865-9ae7-320426090fc7 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal; Production mix, from surface mine | 65ea5547-806a-4557-b1cd-d629d4f0aa66 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal; Production mix, from underground mine | 31c2fb00-53ac-4ab1-984d-dd9791b7ca0f | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal; Handled; From underground mine | 8bf6708a-0a0f-41e4-9b1a-54a92b11dd21 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Overburden removal; Surface coal mine | 823bb844-8ad2-4f66-a8e2-d4f76977a54e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal loading silo; Manufacture; For railcar loading of coal, surface mine | 7936602f-ab84-41ee-9902-28c7e5ed2efc | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal loading silo; Manufacture; For railcar loading of coal, underground mine; 295 metric tonnes | 1e6590e6-3cde-4c02-8b77-775f62938c81 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Fuel consumption and emissions from coal mine commissioning and decommissioning; Surface mine | 488bfccd-c180-4702-a649-ecc91e7fd8ad | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Fuel consumption and emissions from coal mine commissioning and decommissioning; Underground mine | 1690836c-f0b6-4c49-8ca8-a46527615316 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal mine equipment assembly; Production mix, surface mine | b877055b-0dee-4718-ac5a-b6c8dbee3f5f | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal mine equipment assembly; Production mix, underground mine | 6b2ebd41-6faa-4963-b6ab-cb4f57857498 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Methane emission; Production mix, surface mine | 7c2aefa4-0347-4e4b-b9bb-febc2b3f146d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Methane emission; Production mix, underground mine | 75851c42-093d-423a-947d-359780a2359d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal mine site construction; Concrete structures and asphalt paving; Underground mine | 234c2704-8e9c-45f3-92cd-89035953e083 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal mine tailings storage and disposal; Production mix, underground mine | edb2b1ea-9734-464c-aaf7-a3e94c28a1a8 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal mine ventilation energy; Electric fan; Underground mine | 1e130b16-58df-43f3-a504-6c1c07a03d6d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Water use and quality; Production mix, from surface coal mine | c4d3dac4-5661-4997-8f9d-bf9f7b07041d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Water use and quality; Production mix, from underground coal mine | c9362cd7-39cc-438b-81c4-5354f42f9abc | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal preparation facility; Multiple processes; Underground mine | 22ec671a-a857-4de0-a407-69df8f4b1bc9 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal shuttle car; Manufacture; For underground mine, at plant; 28.6 metric tonnes | e6d050ce-8a42-413a-a901-63911e9c15c8 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal; Cleaned; Underground mine | 756647e7-8bf4-49d8-9190-7d9cf39a2345 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Land reclamation; Surface coal mine | 9379792a-be43-4696-b84f-232a859f053c | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Overburden removal; Surface coal mine | 823bb844-8ad2-4f66-a8e2-d4f76977a54e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Wastewater treatment plant; Construction; For underground coal mine | cd849219-78fa-4d47-b4ae-4bccf0f36384 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Thermal energy; From diesel fired equipment; Production mix | ee49c996-8c8f-4d0c-b21f-67e58400cd5a | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Stainless steel; Manufacture; Production mix, at plant; 316 2B, 80% recycled | 69fece29-f722-4dc4-acfb-a9cbbebfcb11 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Steel plate; Blast furnace route; Production mix; 85% recovery rate | f5fc0230-23b0-41e8-8583-266c8c92f2c6 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Steel reinforcement bar; Blast furnace route; Production mix | be127e1f-720b-4e31-82ee-4499e2714d11 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Coal stockpile stacker;  Manufacture; At point-of-sale | 05d561dd-1ab2-4b17-a929-d5a7890b3735 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Continuous coal miner; Manufacture; At underground mine; 563 kW | 1441bee2-63f1-45b3-add2-3476bd85ca7e | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Dragline; Manufacture; For surface coal mine, at plant; 7,439 metric tonne working weight | b8510d02-4ba2-4a6c-9670-738478f57e5d | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Electric head drive; Manufacture; For underground coal mine, at plant | 6dc31dc8-4a61-45ef-9b10-c60b79b1ecdc | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Electric shearer; Manufacture; For underground coal mine, at plant | 522bf26b-3e3b-4a93-afc8-c7a3b45f0f26 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Electric shovel; Manufacture; For surface coal mine, at plant; 109 metric tonne payload | c64cfcaa-9404-4212-a4c2-dc9c490bd769 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Electric stage loader; Manufacture; For underground coal mine, at plant | 0391748e-38d3-4e0c-aa4b-9f5ca637e007 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Electric tail drive; Manufacture; For underground coal mine, at plant | 98dd6647-7a96-4638-afe5-3394b8e73057 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Hydraulic shield; Manufacture; For underground coal mine, at plant; 2 m width | 8f4525b6-b3a3-448a-9eeb-6fb0746329fb | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Line pan; Manufacture; For underground coal mine, at plant | 971deb40-0977-45af-bd8b-f68f90ad66d1 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Longwall mining system; Equipment assembly; Production mix, at underground coal mine | cbe2bbb2-4102-4b11-bdfd-d38b28033496 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Mining truck; Manufacture; For surface mine, at plant; Gross machine operating weight  623,690 kg | 2ed3f4de-b092-4bbf-b47b-27eedc904370 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Track loader; Manufacture; At point-of-sale; 178 kW | 7d328575-1988-4b96-88eb-6a3474077ede | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q3.01 | Product | Deletion | Tractor-propelled coal crusher;  Manufacture; For surface mine, at plant | 8f9ae883-1cd1-49f7-8f73-dc5374ddcf31 | Phase out coal data as superseded by NETL repo coal data on the Federal LCA Commons |
| FY19.Q2.01 | Process | Revision | Hydrogen, liquid, synthesis gas, at plant | 4eaec911-05e8-304e-b7a6-98ce06fc9820 | Corrected server display of  for missing decimal in carbon dioxide air emissions (i.e., 800000 corrected to 8.00 kg/1kg) |
| FY19.Q2.01 | Process | Deletion | Crude oil, at refinery | dc72e285-719b-318b-9c9c-c838846a9cf4 | Deleted outdated provider |
| FY19.Q2.01 | Process | Revision | Petroleum refining, at refinery - RNA | 0aaf1e13-5d80-37f9-b7bb-81a6b8965c71 | Physical allocation applied as a default |
| FY19.Q2.01 | Process | Revision | Dry rough lumber, at kiln, US PNW - RNA | 6951704b-be4b-313d-9965-8561760f733f | Physical allocation applied as a default |
| FY19.Q2.01 | Process | Revision | Dry rough lumber, at kiln, US SE - RNA | f337d438-49db-3078-b1dd-3e6e7ca1e9b5 | Physical allocation applied as a default |
| FY19.Q2.01 | Process | Revision | Railroad tie, hardwood, rough, green, at sawmill, SE - RNA | bbb16d92-dd0c-33c5-92c7-feca45646d83 | Physical allocation applied as a default |
| FY19.Q2.01 | Process | Revision | Railroad ties, hardwood, creosote treated, SE | a24e59f5-c156-398d-9a15-7d853ef2bf37 | Physical allocation applied as a default |
| FY19.Q2.01 | Process | Deletion | Acrylonitrile-butadiene-styrene copolymer, resin, at plant | cd082abe-1655-3803-9a92-e951947a3034 | Deleted outdated provider |
| FY19.Q2.01 | Process | Deletion | Methylene diphenyl diisocyanate, resin, at plant | 8b7ca8cd-d3f5-32de-acd1-866da60df926 | Deleted outdated provider |
| FY19.Q2.01 | Process | Deletion | Polyethylene terephthalate, resin, at plant | 7b69255a-a7b2-318e-9433-54b7c4d13ece | Deleted outdated provider |
| FY19.Q2.01 | Process | Deletion | Polyethylene, high density, resin, at plant | d7c36a39-fdcc-3eb8-a8cd-c6c2b5a11c9a | Deleted outdated provider |
| FY19.Q2.02 | Process | Deletion | Polyethylene, linear low density, resin, at plant | 22b1bab0-c987-3728-9c44-f383f9ef98c7 | Deleted outdated provider |
| FY19.Q2.03 | Process | Deletion | Polyethylene, low density, resin, at plant | 05561830-e889-31a3-b2be-7c52ee2ea545 | Deleted outdated provider | 
| FY19.Q2.04 | Process | Deletion | Polyol ether, for flexible foam polyurethane production, at plant | 51f92626-bf53-307b-9f7b-50c1c64ee887 | Deleted outdated provider |
| FY19.Q2.05 | Process | Deletion | Polyol ether, for rigid foam polyurethane production, at plant | 7f4424b8-da85-3804-ad14-2650343af83c | Deleted outdated provider |
| FY19.Q2.06 | Process | Deletion | Polystyrene, general purpose, at plant | dc8ba0cc-e7bb-3e8f-8d07-39f2e873dd24 | Deleted outdated provider |
| FY19.Q2.07 | Process | Deletion | Polystyrene, high impact, resin, at plant | e10de570-42e6-3cb6-98fe-7bf6da57046c | Deleted outdated provider |
| FY19.Q2.08 | Process | Deletion | Polyvinyl chloride, resin, at plant | b19fe3da-392e-36af-9342-910be1d2160a | Deleted outdated provider |
| FY19.Q2.09 | Process | Deletion | Toluene diisocyanate, at plant | 268e1ddf-197a-37d5-b229-e559c2d6c677 | Deleted outdated provider |
| FY19.Q2.01 | Process | Revision | Hydrogen, liquid, synthesis gas, at plant | 4eaec911-05e8-304e-b7a6-98ce06fc9820 | Corrected server display of  for missing decimal in carbon dioxide air emissions (i.e., 800000 corrected to 8.00 kg/1kg) |
| FY18.Q3.01 | Process | New content | Printer, AltaLink B8045/55, multi-functional device (MFD) | 50356d14-b626-4a38-babf-bf5657d08358 | - |
| FY18.Q3.01 | Process | Revision | Corrugated product, 100% recycled, at mill |   | Update to and replacement for the similarly named 2010 process |
| FY18.Q3.01 | Process | Revision | Corrugated product, average production, at mill |   | Update to and replacement for the similarly named 2010 process |
| FY18.Q3.01 | Process | Revision | Containerboard, 100% recycled, at mill |   | RENAMED process by removing &quot;average production&quot; from flow name |
| FY18.Q3.01 | Process | Revision | Containerboard, average production, at mill |   | RENAMED flow and process name to reference only new quantiative flow nomenclature (i.e., sans data year); data year only referenced in temporal data quality fields |
| FY18.Q3.01 | Process | Revision | Corrugated product, containerboard, average production, at mill, 2010 - US |   | DELETED - Archived in older database version |
| FY18.Q3.01 | Process | Revision | Sold electricity, from 100% recycled containerboard (2010) - US |   | Renamed to eliminate the data year |
| FY18.Q3.01 | Process | Revision | Sold electricity, from industry-average containerboard (2010) - US |   | Renamed to eliminate the data year |
| FY18.Q3.01 | Process | Revision | Sold steam, from industry-average containerboard (2010) - US |   | Renamed to eliminate the data year |
| FY18.Q3.01 | Process | Revision | Tall oil, from industry-average containerboard (2010) - US |   | Renamed to eliminate the data year |
| FY18.Q3.01 | Process | New content | Steam, purchased by containerboard mills |   | Process is an input to the updated NCASI Corrugated data |
| FY18.Q3.01 | Process | Revision | Sold electricity, from industry-average containerboard production |   | RENAMED from &quot;Sold electricity, from industry-average containerboard production (2010)&quot; |
| FY18.Q3.01 | Process | Revision | Electricity, Eastern US, 2014 |   | Updated from &quot;Electricity, at grid, Eastern US, 2000&quot; for updated NCASI Corrugated data |
| FY18.Q3.01 | Process | Revision | Electricity, Texas US, 2014 |   | Updated from &quot;Electricity, at grid, Texas, 2000&quot; for updated NCASI Corrugated data |
| FY18.Q3.01 | Process | Revision | Electricity, Western, US 2014 |   | Updated from &quot;Electricity, at grid, Western US, 2000&quot; for updated NCASI Corrugated data |
| FY18.Q3.01 | Process | Revision | Planed dried lumber processing, at planer mill, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Planed dried lumber processing, at planer mill, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Planed green lumber processing, at planer mill, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Composite wood I-joist processing, at plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Engineered flooring, hardwood, unfinished, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Composite wood I-joist processing, at plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Composite wood I-joist processing, at plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Glue laminated beam processing, at plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Glue laminated beam processing, at plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Oriented strand board processsing, at plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Roundwood, hardwood, green, at logyard, SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Roundwood, hardwood, green, at mill, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Roundwood, hardwood, green, at mill, SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Cellulosic fiberboard, uncoated, at plant |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Hardboard, at hardboard plant |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Wood Combusted, at boiler, at cellulosic fiberboard mill |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Wood Combusted, at boiler, at hardboard mill |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Debarking, at plywood plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Debarking, at plywood plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Rough green lumber processing, at sawmill, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Rough green lumber processing, at sawmill, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, hardwood, planed, kiln dried, at planer mill, NE-NC |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, hardwood, planed, kiln dried, at planer mill, SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, hardwood, rough, green, at sawmill, NE-NC |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, hardwood, rough, green, at sawmill, SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, softwood, planed, kiln dried, at planer, NE-NC |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn Lumber, softwood, planed, kiln dried, at planer mill, INW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, softwood, rough, green, at sawmill, INW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Sawn lumber, softwood, rough, green, at sawmill, NE-NC |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Solid strip and plank flooring, hardwood, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Bucked and debarked log, hardwood, green, at veneer mill, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Dry veneer processing, at plywood  plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Green veneer processing, at plywood plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Green veneer processing, at plywood plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Heat, drying veneer, hardwood, at veneer mill, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Laminated veneer lumber processing, at plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Laminated veneer lumber processing, at plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Medium density fiberboard (MDF), at MDF mill |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Particleboard, average, softwood, particleboard mill |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Trim and saw process, at plywood plant, US PNW |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Trim and saw process, at plywood plant, US SE |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Veneer, hardwood, dry, at veneer mill, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | Revision | Veneer, hardwood, green, at veneer mill, E |   | Physical allocation applied as a default |
| FY18.Q3.01 | Process | New content | CUTOFF Pitch despergents, in paper production |   | New input to the updated NCASI Corrugated datasets |
| FY18.Q3.01 | Process | New content | CUTOFF Tire derived fuel |   | Moved from the Paper Manufacturing folder to the CUTOFF folder as Input to the updated NCASI Corrugated datasets |
| FY18.Q3.01 | Process | New content | CUTOFF Unspecified additive |   | New input to the updated NCASI Corrugated datasets |
| FY18.Q3.01 | Flow | New content | Printer, AltaLink B8045/55, multi-functional device (MFD) |   | Quantitative reference  created for new process |
| FY18.Q3.01 | Flow | Revision | Corrugated product, average production, at mill |   | Quantitative reference renamed from &quot;Corugated Product - US&quot; |
| FY18.Q3.01 | Flow | Revision | Corrugated product, 100% recycled, at mill |   | Quantitative reference renamed from &quot;Corrugated Product, 100% Recycled - US&quot; |
| FY18.Q3.01 | Flow | Revision | Steam, purchased by containerboard mills |   | Process is an input to the updated NCASI Corrugated data |
| FY18.Q3.01 | Flow | Revision | Corrugated Product - CH |   | Bulk replaced with CUTOFF Corrugated board, mixed fibre, single wall, at plant - CH and then deleted |
| FY18.Q3.01 | Flow | Revision | Sulfuric acid, dimethyl ester |   | Bulk replaced from air/uspecified folder to IUPAC-named &quot;Dimethyl sulfate&quot; in Elementary Flows folder |
| FY18.Q3.01 | Flow | Revision | 2-Chloroacetophenone |   | Bulk replaced from air/uspecified folder to IUPAC-named &quot;Chloromethylbenzene&quot; in Elementary Flows folder |
| FY18.Q3.01 | Flow | Revision | Toluene, chloro- |   | Bulk replaced from air/uspecified folder to Elementary Flows folder |
| FY18.Q3.01 | Flow | Revision | Ethane, 1,2-dichloro- |   | Bulk replaced from air/uspecified folder to IUPAC-named &quot;2-Chloro-1-phenylethanone&quot; in Elementary Flows folder |
| FY18.Q3.01 | Actor | New content | Alissa Santucci |   | New actor for Xerox printer process |
| FY18.Q3.01 | Actor | New content | Corrugated Packaging Alliance (CPA) |   | New actor for the NCASI Corrugated update |
| FY18.Q3.01 | Actor | New content | Victoria DeYoung |   | New actor for Xerox printer process |
| FY18.Q3.01 | Actor | New content | Xerox Corporation |   | New actor for Xerox printer process |
| FY18.Q3.01 | Source | New content | Guidance on Data Quality Assessment for Life Cycle Inventory Data |   | New source for added processes |
| FY18.Q3.01 | Source | New content | IEEE (2012). 1680.2-2012 - IEEE Standard for Environmental Assessment of Imaging Equipment, 19 Oct. 2012. |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14025:2006: Environmental labels and declarations -- Type III environmental declarations -- Principles and procedures |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14040:2006: Environmental management -- Life cycle assessment -- Principles and framework |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14044:2006: Environmental management -- Life cycle assessment -- Requirements and guidelines |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14064-1:2006: Greenhouse gases -- Part 1: Specification with guidance at the organization level for quantification and reporting of greenhouse gas emissions and removals |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14064-2:2006: Greenhouse gases -- Part 2: Specification with guidance at the project level for quantification, monitoring and reporting of greenhouse gas emission reductions or removal enhancements |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2006). ISO 14064-3:2006: Greenhouse gases -- Part 3: Specification with guidance for the validation and verification of greenhouse gas assertions |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2013). ISO 14065:2013: Greenhouse gases -- Requirements for greenhouse gas validation and verification bodies for use in accreditation or other forms of recognition |   | New source for added processes |
| FY18.Q3.01 | Source | New content | ISO (2018). ISO/TS 14067:2018: Greenhouse gases -- Carbon footprint of products -- Requirements and guidelines for quantification and communication |   | New source for added processes |
| FY18.Q3.01 | Source | New content | PAS 2050 (2011). Specification for the assessment of the life cycle greenhouse gas emissions of goods and services |   | New source for added processes |
| FY18.Q3.01 | Source | New content | WRI (2011). Greenhouse Gas (GHG Protocol: Product Life Cycle Accounting and Reporting Standard. |   | New source for added processes |
| FY18.Q3.01 | Source | New content | Xerox Corporation (2018). Life Cycle Assessment of Xerox AltaLink B8045/B8055/B8065/B8075/B8090, August 2018 |   | New source for added processes |
| FY18.Q1.01 | Actor | New content | EPS Industry Alliance (EPS-IA) | 0b2b785e-5cfd-4331-8711-790742934e47 | - |
| FY18.Q1.01 | Actor | New content | Melissa Huff | f3ce0eca-08f6-4eac-bd6e-cecabe5b4252 | - |
| FY18.Q1.01 | Actor | New content | Franklin Associates, A Division of ERG | 38e67478-a915-43d9-ad67-e25db79a4acc | Updated version of the _Franklin Associates_ actor |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | f238e394-b16d-3194-9c3d-cfd600a1cc95 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 721bcfe4-ee92-33bc-a9bd-bbf5ba3cb52d | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | c4c3ffcf-9ee5-3bc4-994f-87ae13f997a7 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 2b6d62da-50ea-31f4-9085-049cfd4f5023 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 560dc1e7-88e7-3ce3-850a-7a09eb3a46b3 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | fa9a073d-3ea7-3ed9-a63f-d4fe9d0083f6 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 19bec18b-28f6-3be2-bd4d-8fea0328ecb5 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | c5006977-fdaf-3b1c-8000-cd7ebc9d2b62 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 226558a9-73e4-36d4-b383-98230cc5247d | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | 527239d5-96d8-30a3-8dc6-682d306a2669 | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | b122816a-b081-373c-8564-44df6ffec96c | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Actor | Revision | Franklin Associates | c7fc4474-e3a3-34cc-94a0-ea8047189f8c | Replaced with _Franklin Associates, A Division of ERG_ (UUID 38e67478-a915-43d9-ad67-e25db79a4acc) |   
| FY18.Q1.01 | Flow | New content | CUTOFF Disposal, hazardous waste, to incineration with energy recovery | a98db096-441e-4783-900f-b6693ecde0c9 | - |  
| FY18.Q1.01 | Flow | New content | CUTOFF Disposal, hazardous waste, to incineration without energy recovery | ac003090-67b7-4364-b690-807d12019627 | - |  
| FY18.Q1.01 | Flow | New content | CUTOFF Disposal, hazardous waste, to unspecified hazardous waste landfill | 42929598-5cd9-4fac-a79d-fd0ab85a4176 | - |   
| FY18.Q1.01 | Flow | New content | CUTOFF Disposal, solid waste, process, to sanitary landfill | df2b3c59-4923-41b4-ac38-967884123025 | - |
| FY18.Q1.01 | Flow | New content | CUTOFF Disposal, solid waste, to incineration without energy recovery | c3a414cf-44c3-409b-8481-7c0fafdb225c | - |  
| FY18.Q1.01 | Flow | New content | CUTOFF Recycling, solid waste, to recycling or reuse | 8191e38b-421f-4348-a2e0-29303147f2d1 | - |  
| FY18.Q1.01 | Flow | New content | CUTOFF Flame retardant, decaBDE | 5ef7c19f-6cf9-35d2-827c-2f4e2780ce31 | - |   
| FY18.Q1.01 | Flow | New content | CUTOFF Nitrogen, liquid, at plant | bc8e6793-7071-3c12-bac4-bb5adcb44f79 | - |   
| FY18.Q1.01 | Flow | New content | CUTOFF Pentane | 59a964a3-fdbd-3370-b38e-ff79acedbe09 | - |  
| FY18.Q1.01 | Flow | New content | EPS virgin resin; batch suspension polymerization; industry average, at plant | cc5415fd-2095-31f1-8e53-c5fcd2fd8c54 | - |    
| FY18.Q1.01 | Flow | Revision | Natural soda ash (Sodium carbonate), at plant_BAD | c0af8d39-2a03-3e1d-8548-67989e0fda5a | Duplicate with identically named flow (RefID c0af8d39-2a03-3e1d-8548-67989e0fda5a).  All process connections reconnected to RefID c0af8d39-2a03-3e1d-8548-67989e0fda5a. |  
| FY18.Q1.01 | Process | New content | EPS virgin resin manufacture; batch suspension polymerization; industry average, at plant | cf1241fd-8c01-3412-9030-8650b8e75669 | - |  
| FY18.Q1.01 | Source | New content | Franklin Associates. (2016). EPS-IA Cradle-to-Gate Life Cycle Analysis of Expanded Polystyrene Resin | 22bb3d4e-62b7-45e6-9ebd-8f4b52d30df3 | - |   
| FY17.Q4.02 | Actor | New content | Sustainable Solutions Corporation | - | - |    
| FY17.Q4.02 | Actor | Revision | Cara Watson | - | Add metadata |  
| FY17.Q4.02 | Category | Revision | Lime and Gypsum Product Manufacturing | - | Merge categories, "Gypsum product manufacturing" and "Lime Manufacturing", into a single category.  The new category retains "Gypsum product manufacturing" UUID. |  
| FY17.Q4.02 | Flow | Revision | CUTOFF Fatty Acids | - | Correct spelling error in file name |   
| FY17.Q4.02 | Process | New content | Calcium carbonate, ground, 20 micron, at plant | - | - |    
| FY17.Q4.02 | Process | New content | Calcium carbonate, ground, 30 micron, at plant | - | - |    
| FY17.Q4.02 | Process | New content | Calcium carbonate, ground, fine treated, 3 micron, at plant | - | - |
| FY17.Q4.02 | Process | New content | Calcium carbonate, ground, fine slurry, 3 micron, at plant | - | - |    
| FY17.Q4.02 | Process | New content | Calcium carbonate, ground, screened grade, at plant | - | - |    
| FY17.Q4.02 | Process | Revision |Natural soda ash (Sodium carbonate), at plant | - | Correct units error for exchange, "Natural soda ash (Sodium carbonate), at plant" |    
| FY17.Q4.02 | Source | Revision | Sustainable Solutions Corporation. (2015). IMA-NA Soda Ash Life Cycle Assessment  | - | Add metadata |   
| FY17.Q4.02 | Source | New content | Sustainable Solutions Corporation. (2016). IMA-NA Calcium Carbonate Life Cycle Assessment | - | - |
| FY17.Q4.02 | Source | Revision | Wood. (2016). Greenhouse Gas Life Cycle Assessment Summary Report - Kodak Alaris i710, i703EX, i940, i1150, i1150WN, i1190,i1190E, i1190WN Scanners, ISO 14044 Protocol  | - | Add URL |    

<br><br>


[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

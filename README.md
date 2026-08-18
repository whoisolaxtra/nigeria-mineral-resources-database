# Nigeria Mineral Resources Database

A structured database of mineral occurrence records in Nigeria compiled from the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Overview

This repository provides a structured and organised database of mineral occurrence records represented in the NGSA *Mineral Resources Map of Nigeria* (2023).

The original Excel database was created from scratch by **whoisOlaxtra** through manual extraction and structuring of mineral occurrence localities and resource types presented in the NGSA 2023 map. Because the source was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable database, the occurrence information was manually interpreted, transcribed and organised into an Excel workbook.

The original database was subsequently reviewed against the NGSA 2023 map to identify occurrence records that had not been captured during the initial compilation. The identified records were added to the database while preserving the established workbook structure and formatting.

The resulting dataset is intended to support GIS, geospatial analysis, mineral-resource research, spatial data management and related applications.

## Dataset

The current database contains **974 mineral occurrence records**.

The principal database is provided as an Excel workbook:

`data/Nigeria_Mineral_Resources_Database.xlsx`

The current database contains the records represented in the workbook after the subsequent comparison and update process. The highest `Occurrence_ID` is **1045**; this should not be interpreted as the total number of records because the identifier sequence contains gaps.

## Original Source

The external source used to create and update the database is:

**Nigeria Geological Survey Agency (NGSA). (2023). *Mineral Resources Map of Nigeria*.**

Official source:

https://ngsa.gov.ng/wp-content/uploads/2023/08/Mineral_Resources_Map_of_Nigeria_2023.pdf

NGSA website:

https://ngsa.gov.ng/

## Database Compilation

The original Excel database was created from scratch by **whoisOlaxtra** using the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023) as the source document.

Because the source material was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable database, mineral occurrence localities and resource types were manually extracted, interpreted and structured into an Excel database.

The subsequent update involved:

- reviewing the original database against the NGSA 2023 map;
- checking mineral occurrence localities and resource types represented in the source map;
- identifying occurrence records not captured in the initial compilation;
- adding the identified missing records to the workbook;
- retaining the established workbook structure and formatting;
- preserving source terminology and occurrence codes where applicable; and
- documenting the source and provenance of the compiled records.

## Attribution and Ownership

The original Excel database and its structure were created by **whoisOlaxtra** through the manual extraction, transcription, organisation and structuring of mineral occurrence information represented in the NGSA *Mineral Resources Map of Nigeria* (2023).

The author's contribution includes the creation and organisation of the workbook, manual extraction and transcription of occurrence information from the source map, structuring of the database, subsequent comparison against the source map, identification and addition of missing records, standardisation where applied, and documentation of the resulting dataset.

The **Nigeria Geological Survey Agency (NGSA)** is recognised as the source authority for the mineral occurrence information depicted on the 2023 map.

This repository does not claim ownership of the NGSA map, its cartographic design, or the underlying geological information originating from NGSA.

The database published in this repository is the author's structured compilation and organisation of information obtained from the cited NGSA source.

### Recommended attribution

> Mineral occurrence information: Nigeria Geological Survey Agency (NGSA), *Mineral Resources Map of Nigeria* (2023). Database compilation and structuring: whoisOlaxtra.

## Data Provenance

The provenance of the database can be represented as follows:

**NGSA Mineral Resources Map of Nigeria (2023)**  
→ **manual extraction and transcription from the PDF map**  
→ **original Excel database created and structured by whoisOlaxtra**  
→ **comparison and completeness review against the source map**  
→ **identification and addition of records not captured in the initial compilation**  
→ **updated structured database**

The source material was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable database. Consequently, the creation of the database involved manual interpretation and transcription of mineral occurrence localities and resource types represented on the map.

The NGSA map remains the external source for the mineral occurrence information represented in the source material. The Excel database, its structure, organisation, compilation and documentation are the work of **whoisOlaxtra**.

## Limitations

This database is a structured compilation of mineral occurrence information interpreted from the NGSA *Mineral Resources Map of Nigeria* (2023).

Because the source material is a cartographic product in PDF format, the database is dependent on the information that can be identified and interpreted from the published map. It should therefore not be treated as a replacement for the original NGSA map or for official geological datasets that may subsequently become available.

The database represents mineral occurrence information and should not be interpreted as a statement of current mineral reserves, deposit size, grade, economic viability, production status or commercial potential.

The database should not be interpreted as an independently verified geological survey. Users requiring authoritative or current geological and mineral-resource information should consult the Nigeria Geological Survey Agency and its official publications.

Spatial analysis based on the database should account for the positional and interpretive limitations associated with extracting information from a cartographic source.

## Intended Uses

The database is intended to provide a structured starting point for:

- GIS and geospatial analysis;
- mineral-resource mapping;
- spatial analysis of mineral occurrences;
- academic and research applications;
- environmental and resource-management studies;
- exploratory spatial analysis; and
- development of GIS-based mineral-resource inventories.

The database can be incorporated into GIS workflows where a structured tabular representation of mineral occurrence information is required.

Users should independently assess the suitability, completeness and positional accuracy of the database for their specific application.

## Repository Structure

The repository is organised to separate the database from its supporting documentation and source information.

```text
nigeria-mineral-resources-database/
│
├── README.md
│
├── data/
│   └── Nigeria_Mineral_Resources_Database.xlsx
│
├── sources/
│   └── NGSA_SOURCE.md
│
└── documentation/
    ├── DATA_DICTIONARY.md
    ├── DATA_PROVENANCE.md
    └── METHODOLOGY.md

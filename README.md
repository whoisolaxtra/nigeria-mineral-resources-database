# Nigeria Mineral Resources Database

A structured database of mineral occurrence records in Nigeria compiled from the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Overview

This repository provides a structured and organised database of mineral occurrence records presented in the NGSA Mineral Resources Map of Nigeria (2023).

The original Excel database was created from scratch by whoisOlaxtra through manual extraction and structuring of mineral occurrence locality and resource-type information presented in the Nigeria Geological Survey Agency (NGSA) Mineral Resources Map of Nigeria (2023). The resulting workbook was subsequently reviewed against the source map to identify occurrence records that had not been captured in the initial compilation, and the missing records were appended while preserving the established workbook structure.

The resulting dataset is intended to support GIS, geospatial analysis, mineral-resource research, spatial data management and related applications.

## Dataset

The current release contains **1045 mineral occurrence records**.

The principal database is provided as an Excel workbook:

`data/Nigeria_Mineral_Resources_Database.xlsx`

## Original Source

The original mineral occurrence information was derived from:

**Nigeria Geological Survey Agency (NGSA). (2023). _Mineral Resources Map of Nigeria_.**

Official source:

https://ngsa.gov.ng/wp-content/uploads/2023/08/Mineral_Resources_Map_of_Nigeria_2023.pdf

NGSA website:

https://ngsa.gov.ng/

## Database Compilation

The original Excel database was created from scratch by **whoisOlaxtra** using the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023) as the source document.

Because the source material was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable database, the mineral occurrence information was manually extracted from the map and structured into an Excel database.

The subsequent update involved:

- reviewing the original database against the NGSA 2023 map;
- checking mineral occurrence localities and resource types represented in the source map;
- identifying occurrence records not captured in the initial database;
- adding the missing records to the workbook;
- retaining the established workbook structure and formatting;
- preserving source terminology and occurrence codes where applicable; and
- documenting the source and provenance of the compiled records.

## Attribution and Ownership

The original Excel database was created and structured by **whoisOlaxtra** through manual extraction and organisation of mineral occurrence information presented in the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

The author's contribution includes the creation of the workbook structure, manual extraction and transcription of occurrence information from the source map, organisation of the records, subsequent comparison with the source map, identification and addition of missing records, and documentation of the resulting database.

The **Nigeria Geological Survey Agency (NGSA)** is recognised as the original source of the mineral occurrence information depicted on the 2023 map.

This repository does not claim ownership of the NGSA map, its cartographic design, or the underlying geological information originating from NGSA.

The database published in this repository is an independently created and structured compilation based on the cited NGSA source.

### Recommended attribution

> Mineral occurrence information: Nigeria Geological Survey Agency (NGSA), *Mineral Resources Map of Nigeria* (2023). Database compilation and structuring: whoisOlaxtra.

## Data Provenance

**whoisOlaxtra** initially created the database through manual extraction and transcription of mineral occurrence localities and resource types presented in the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

The source material was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable database. The information represented in the map was therefore manually interpreted and structured into an Excel workbook.

The completed workbook was subsequently reviewed against the NGSA 2023 map to identify occurrence records that were not captured during the initial extraction. The identified records were added to the database while maintaining the established workbook structure and formatting.

The provenance chain is therefore:

**NGSA Mineral Resources Map of Nigeria (2023)**  
→ **manual extraction and transcription**  
→ **original Excel database created by whoisOlaxtra**  
→ **comparison and completeness review against the source map**  
→ **addition of identified missing records**  
→ **updated structured database**

The NGSA map remains the external source for the mineral occurrence information represented in the source material. The Excel database and its organisation, structure and compilation are the work of **whoisOlaxtra**.

**Original source**

Nigeria Geological Survey Agency (NGSA), 2023.

**Database compilation**

whoisOlaxtra — extraction, comparison, structuring, organisation, standardisation, documentation and publication.

The database should therefore not be interpreted as an independent geological survey or as a replacement for the official NGSA map.

## Limitations

This database is a structured compilation of mineral occurrence information interpreted from the NGSA Mineral Resources Map of Nigeria (2023).

Because the source material is a map in PDF format, the database is dependent on the information that can be identified and interpreted from the published map. It should therefore not be treated as a replacement for the original NGSA map or for official geological datasets that may subsequently become available.

The database represents mineral occurrence information and should not be interpreted as a statement of current mineral reserves, deposit size, grade, economic viability, production status or commercial potential.

The database should also not be interpreted as an independently verified geological survey. Users requiring authoritative or current geological and mineral-resource information should consult the Nigeria Geological Survey Agency and its official publications.

Spatial analysis based on the database should account for the positional and interpretive limitations associated with extracting information from a cartographic source.

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

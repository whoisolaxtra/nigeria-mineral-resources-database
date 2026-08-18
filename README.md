# Nigeria Mineral Resources Database

A structured database of mineral occurrence records in Nigeria compiled from the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Overview

This repository provides a structured and organised database of mineral occurrence records presented in the NGSA Mineral Resources Map of Nigeria (2023).

The original Excel database was created from scratch by whoisOlaxtra through manual extraction and structuring of mineral occurrence locality and resource-type information presented in the Nigeria Geological Survey Agency (NGSA) Mineral Resources Map of Nigeria (2023). The resulting workbook was subsequently reviewed against the source map to identify occurrence records that had not been captured in the initial compilation, and the missing records were appended while preserving the established workbook structure.

The resulting dataset is intended to support GIS, geospatial analysis, mineral-resource research, spatial data management and related applications.

## Dataset

The current release contains **974 mineral occurrence records**.

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

The database was compiled and structured by **whoisOlaxtra**.

The compilation process involved:

- manual extraction from the PDF map;
- transcription of occurrence localities;
- transcription of mineral/resource types;
- creation of the Excel database structure;
- comparison/review against the source map;
- identification of omitted records;
- addition of missing records;
- standardisation and organisation;
- preservation of source codes/terminology where applicable.

## Attribution and Ownership

The original mineral occurrence information presented by the NGSA remains attributable to the **Nigeria Geological Survey Agency (NGSA)**.

This repository does **not** claim ownership of the original NGSA map or the underlying source information contained within it.

The Excel database was created and structured by whoisOlaxtra through manual extraction and organisation of information presented in the NGSA Mineral Resources Map of Nigeria (2023). NGSA is acknowledged as the original source of the mineral occurrence information represented in the map.

The author's contribution to this repository consists of the compilation, organisation, structuring, cleaning, documentation and publication of the database derived from the cited NGSA source.

When using this database, users should acknowledge both the original NGSA source and this database compilation.

### Recommended attribution

> Mineral occurrence information: Nigeria Geological Survey Agency (NGSA), *Mineral Resources Map of Nigeria* (2023). Database compilation and structuring: whoisOlaxtra.

## Data Provenance

The database represents a compiled secondary dataset derived from the NGSA 2023 mineral resources map.

The repository maintains a distinction between:

**Original source**

Nigeria Geological Survey Agency (NGSA), 2023.

**Database compilation**

whoisOlaxtra — extraction, comparison, structuring, organisation, standardisation, documentation and publication.

The database should therefore not be interpreted as an independent geological survey or as a replacement for the official NGSA map.

## Limitations

The database is a structured compilation of mineral occurrence information represented in the source map.

It should not be interpreted as a statement of current mineral reserves, economic viability, production status, deposit size, grade or commercial potential.

Users requiring authoritative geological or mineral-resource information should consult the original NGSA publications and datasets.

The spatial representation and terminology of the database are dependent on the information available in the source material.

## Repository Structure

```text
nigeria-mineral-resources-database/
│
├── README.md
│
├── data/
│   └── Nigeria_Mineral_Resources_Database.xlsx
│
├── documentation/
│   ├── DATA_DICTIONARY.md
│   ├── DATA_PROVENANCE.md
│   └── METHODOLOGY.md
│
├── sources/
│   └── NGSA_SOURCE.md
│
├── CITATION.cff
└── LICENSE

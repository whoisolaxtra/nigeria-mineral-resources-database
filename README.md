# Nigeria Mineral Resources Database

A structured database of mineral occurrence records in Nigeria compiled from the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Overview

This repository provides a structured and organised database of mineral occurrence records presented in the NGSA Mineral Resources Map of Nigeria (2023).

The database was developed by comparing an existing mineral resources workbook against the NGSA 2023 map and adding records identified as missing from the existing database.

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

- reviewing the existing mineral resources workbook;
- comparing the existing records with the NGSA 2023 mineral resources map;
- identifying mineral occurrence records absent from the existing workbook;
- appending the missing records;
- retaining the NGSA occurrence terminology and source codes where available;
- structuring the records into a consistent tabular database;
- documenting the source and provenance of the resulting dataset.

## Attribution and Ownership

The original mineral occurrence information presented by the NGSA remains attributable to the **Nigeria Geological Survey Agency (NGSA)**.

This repository does **not** claim ownership of the original NGSA map or the underlying source information contained within it.

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

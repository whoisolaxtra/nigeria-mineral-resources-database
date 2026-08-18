# Database Compilation Methodology

## Overview

The Nigeria Mineral Resources Database was compiled from mineral occurrence information represented in the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

The database was created manually because the source material was available as a PDF map rather than as a structured spreadsheet, CSV, shapefile, GeoJSON or other machine-readable mineral-occurrence database.

The compilation process consisted of source-map interpretation, manual extraction, database structuring, completeness review and incorporation of identified missing records.

## Compilation Workflow

The database compilation workflow was:

```text
NGSA Mineral Resources Map of Nigeria (2023)
                    |
                    v
             Source map review
                    |
                    v
       Manual occurrence extraction
                    |
                    v
       Original Excel database
                    |
                    v
       Source-map comparison
                    |
                    v
      Identification of missing records
                    |
                    v
       Addition of identified records
                    |
                    v
          Final structured database
```

## 1. Source Map Review

The NGSA *Mineral Resources Map of Nigeria* (2023) was used as the principal external source.

The map was examined to identify mineral occurrence localities and the mineral/resource information associated with those localities.

The source map contains occurrence information represented through locality labels, mineral/resource names and associated codes.

## 2. Manual Extraction

Mineral occurrence information was manually extracted from the PDF map.

For each identifiable occurrence, the relevant information was transcribed into the database, including:

- state;
- locality;
- mineral/resource type; and
- original mineral/resource code where applicable.

The extraction process involved interpreting the cartographic labels and symbols presented on the source map.

## 3. Database Structuring

The extracted information was organised into a structured Excel workbook.

The database contains the following fields:

```text
Occurrence_ID
State
Locality
Mineral
Original Code
Commodity Group
Source

```
Each row represents a mineral occurrence record.

An Occurrence_ID was assigned to distinguish records within the compiled database.

The Original Code field was retained to preserve the relationship between the compiled record and the terminology used on the source map.

## 4. Commodity Classification

Mineral/resource records were organised into broader commodity groups where applicable.

The Commodity Group field provides a higher-level classification that supports grouping and analysis of individual mineral/resource occurrences.

The commodity grouping is part of the database structuring process and should not be interpreted as a replacement for the original NGSA source classification.

## 5. Completeness Review

After creation of the original workbook, the database was reviewed against the NGSA 2023 map.

The purpose of this stage was to identify occurrence records represented on the source map that had not been captured during the initial manual extraction.

The review involved checking the source map against the existing database and examining occurrence localities and associated mineral/resource information.

## 6. Missing Record Identification

Where an occurrence represented on the NGSA map was not represented in the original database, the record was identified as a missing occurrence record.

The relevant information was then manually extracted from the source map and prepared for inclusion in the database.

## 7. Database Update

The identified missing records were appended to the existing workbook.

During the update:

- the established workbook structure was retained;
- existing field names were preserved;
- source terminology was retained where applicable;
- original occurrence codes were preserved where available; and
- the existing database organisation and formatting were maintained.

The objective was to improve the completeness of the original compilation without changing its established structure.

## 8. Quality Checks

The updated database was reviewed to check the consistency of the compiled records.

Checks included:

- reviewing state names;
- reviewing locality names;
- checking mineral/resource names;
- checking original source codes where available;
- checking commodity-group assignments;
- checking record identifiers; and
- checking that the final workbook retained the established field structure.

These checks were intended to reduce transcription and organisation errors arising from manual extraction.

## 9. Final Database

The resulting database contains 974 mineral occurrence records.

The highest Occurrence_ID is 1045. The identifier sequence contains gaps, and therefore the highest identifier should not be interpreted as the number of records.

The final database is provided as:

data/Nigeria_Mineral_Resources_Database.xlsx

## Methodological Limitations

The database was compiled through manual interpretation and transcription of information from a PDF map.

Consequently, the database may inherit limitations associated with:

- cartographic representation;
- map readability;
- source-map labelling;
- manual transcription;
- interpretation of mineral/resource codes;
- locality-name interpretation; and
- the level of detail available in the source map.

The database should therefore be regarded as a structured compilation of information represented in the NGSA 2023 map rather than as an independent geological survey.

The database does not provide independent verification of mineral reserves, deposit size, grade, economic viability, production status or commercial potential.

## Reproducibility

The database can be reproduced in principle by using the cited NGSA 2023 map as the source document and following the documented extraction and structuring workflow.

However, because the original source is a cartographic PDF and the extraction process involved manual interpretation, exact reproduction may depend on how individual map labels and occurrence information are interpreted.

## Relationship to the Original Source

The NGSA Mineral Resources Map of Nigeria (2023) remains the external source for the mineral occurrence information represented in the database.

The database compilation, structuring, organisation, manual transcription, completeness review and documentation were carried out by whoisOlaxtra.

For detailed source attribution and provenance information, see:

For detailed source attribution and provenance information, see:

For detailed source attribution and provenance information, see:

- [README](../README.md)
- [NGSA Source](../sources/NGSA_SOURCE.md)

# Data Dictionary

## Nigeria Mineral Resources Database

This document describes the fields contained in the `Nigeria_Mineral_Resources_Database.xlsx` workbook.

The database contains structured mineral occurrence records compiled from the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Database Fields

| Field | Description | Example |
|---|---|---|
| `Occurrence_ID` | Unique sequential identifier assigned to each mineral occurrence record in the compiled database. | `1` |
| `State` | Nigerian state in which the mineral occurrence locality is identified on the source map. | `Adamawa` |
| `Locality` | Locality or place name associated with the mineral occurrence as represented in the source map. | `Guyuk` |
| `Mineral` | Mineral or mineral-resource type associated with the occurrence. | `Bentonite` |
| `Original Code` | Mineral/resource code associated with the occurrence in the NGSA source map. | `Bn` |
| `Commodity Group` | Broad commodity classification assigned to the mineral/resource occurrence. | `Industrial Mineral` |
| `Source` | Identifies the principal source from which the occurrence information was compiled. | `NGSA 2023` |

## Field Details

### Occurrence_ID

A unique identifier assigned to each record in the compiled database.

The identifier is used to distinguish individual occurrence records within the workbook. It is a database identifier created as part of the compilation and structuring process and does not represent an original NGSA occurrence code.

### State

The Nigerian state associated with the mineral occurrence.

State names are organised as a separate field to support filtering, aggregation and state-level GIS or statistical analysis.

### Locality

The locality associated with the mineral occurrence as represented on the NGSA Mineral Resources Map of Nigeria (2023).

Locality names are retained from the source material as interpreted during manual extraction and structuring.

### Mineral

The mineral or mineral-resource type associated with the occurrence.

The field represents the resource name corresponding to the occurrence information presented on the NGSA source map.

### Original Code

The source mineral/resource code associated with the occurrence.

Where a code is represented on the NGSA map, it is retained in this field to preserve the relationship between the compiled database record and the source map terminology.

Examples include:

- `Bn` — Bentonite
- `Gy` — Gypsum
- `Ls` — Limestone
- `Cl` — Clay
- `Sn` — Sillimanite
- `Ba` — Barite

### Commodity Group

A broader classification used to group individual mineral/resource types into commodity categories.

This field supports grouping and analysis of mineral occurrences at a broader commodity level rather than only by individual mineral type.

### Source

Identifies the principal source of the mineral occurrence information represented by the record.

For the current database, the source is recorded as:

`NGSA 2023`

This refers to the Nigeria Geological Survey Agency (NGSA) *Mineral Resources Map of Nigeria* (2023).

## Data Structure

The database is organised as a flat tabular dataset in which each row represents a mineral occurrence record and each column represents an attribute describing that occurrence.

The principal relationship is:

**Occurrence → State → Locality → Mineral → Original Code → Commodity Group → Source**

## Interpretation Notes

The `Occurrence_ID` is an identifier created for the compiled database and should not be confused with the mineral occurrence numbering or coding system represented on the original NGSA map.

The `Original Code` field preserves the source-map coding where applicable.

The `Mineral` field provides the interpreted mineral/resource name associated with the corresponding source code.

The `Source` field records the principal source used for compiling the database and does not imply that the database itself was produced by NGSA.

## Data Provenance

The database fields were structured by **whoisOlaxtra** during the manual compilation of mineral occurrence information from the NGSA *Mineral Resources Map of Nigeria* (2023).

The original mineral occurrence information remains attributable to the Nigeria Geological Survey Agency (NGSA).

For detailed information on the source, compilation process, attribution and limitations, see:

- `README.md`
- `sources/NGSA_SOURCE.md`

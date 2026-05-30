# `ERCHO`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 6 SELECT statements across 5 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ercho/) — validated 2026-05-30, schema v1.0
**Schema fields:** 7 fields | **Data types:** CHAR(4), DATS(1), DEC(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `VALIDATION` | VALIDATION | TE007 | CHAR | 10 | 0 | Name of billing validation |
| `MANOUTSORT` | MANOUTSORT | TE127 | CHAR | 8 | 0 | Reason for manual outsorting in billing |
| `FREI_AM` | FREI_AM | — | DATS | 8 | 0 | Document Release Date |
| `FREI_VON` | FREI_VON | — | CHAR | 12 | 0 | Name of user who released the document |
| `DEVIATION` | DEVIATION | — | DEC | 13 | 2 | Deviation |
| `SIMULATION` | SIMULATION | — | CHAR | 2 | 0 | Indicator: billing simulation |
| `OUTCOUNT` | OUTCOUNT | — | NUMC | 2 | 0 | Number of manual outsortings to be carried out yet |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANOUTSORT` | SYST | MANDT | TE127 |  | |
| `MANOUTSORT` | ERCHO | MANOUTSORT | TE127 |  | |
| `VALIDATION` | SYST | MANDT | TE007 |  | |
| `VALIDATION` | ERCHO | VALIDATION | TE007 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `belnr`, `validation`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `validation`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbildocaut.txt`
- `zisbi0041.txt`
- `zisbi0214f01.txt`
- `zisdm0172.txt`
- `zreaexcep.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
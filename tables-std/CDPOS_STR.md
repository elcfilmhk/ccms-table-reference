# `CDPOS_STR`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 30 SELECT statements across 2 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/cdpos_str/) — validated 2026-05-30, schema v1.0
**Schema fields:** 14 fields | **Data types:** CHAR(7), LANG(1), RSTR(2), SSTR(2), STRG(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `OBJECTCLAS` | CDOBJECTCL | — | CHAR | 15 | 0 | Object class |
| `OBJECTID` | CDOBJECTV | — | CHAR | 90 | 0 | Object value |
| `CHANGENR` | CDCHANGENR | CDHDR | CHAR | 10 | 0 | Document change number |
| `TABNAME` | TABNAME | — | CHAR | 30 | 0 | Table Name |
| `TABKEY` | CDTABKEYLO | — | CHAR | 254 | 0 | Table Key for CDPOS in Character 254 |
| `FNAME` | FIELDNAME | — | CHAR | 30 | 0 | Field Name |
| `CHNGIND` | CDCHNGIND | — | CHAR | 1 | 0 | Change Type (U, I, S, D) |
| `LANGU` | SPRAS | — | LANG | 1 | 0 | Language Key |
| `VALUE_OLD` | CDSTRINGVALO | — | STRG | 0 | 0 | Old Change Document Value for STRING Variable |
| `VALUE_NEW` | CDSTRINGVALN | — | STRG | 0 | 0 | New Change Document Value for STRING Variable |
| `VALUE_RAWSTR_OLD` | CDRAWSTRINGO | — | RSTR | 0 | 0 | Old Change Document Value for RAWSTRING Variable |
| `VALUE_RAWSTR_NEW` | CDRAWSTRINGN | — | RSTR | 0 | 0 | New Change Document Value for RAWSTRING Variable |
| `VALUE_SHSTR_OLD` | CDSHORTSTRINGO | — | SSTR | 255 | 0 | Old Change Document Value for SHORTSTRING Variable |
| `VALUE_SHSTR_NEW` | CDSHORTSTRINGN | — | SSTR | 255 | 0 | New Change Document Value for SHORTSTRING Variable |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CHANGENR` | CDPOS_STR | MANDANT | CDHDR |  | |
| `CHANGENR` | CDPOS_STR | OBJECTCLAS | CDHDR |  | |
| `CHANGENR` | CDPOS_STR | OBJECTID | CDHDR |  | |
| `CHANGENR` | CDPOS_STR | CHANGENR | CDHDR |  | |
| `MANDANT` | CDPOS_STR | MANDANT | T000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisdm0078f01.txt`
- `zisdm0414f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
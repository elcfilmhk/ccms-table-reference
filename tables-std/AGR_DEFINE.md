# `AGR_DEFINE`

**Description:** Authorization Group Definition — role definitions
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 7 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/agr_define/) — validated 2026-05-30, schema v1.0
**Schema fields:** 10 fields | **Data types:** CHAR(4), DATS(2), DEC(2), TIMS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `PARENT_AGR` | PAR_AGR | AGR_DEFINE | CHAR | 30 | 0 | Name of imparting role |
| `CREATE_USR` | SYUNAME | — | CHAR | 12 | 0 | User Name |
| `CREATE_DAT` | MENU_DATE | — | DATS | 8 | 0 | Date of menu generation |
| `CREATE_TIM` | MENU_TIME | — | TIMS | 6 | 0 | Time when the menu was generated last |
| `CREATE_TMP` | RSTIMESTMP | — | DEC | 15 | 0 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| `CHANGE_USR` | SYUNAME | — | CHAR | 12 | 0 | User Name |
| `CHANGE_DAT` | MENU_DATE | — | DATS | 8 | 0 | Date of menu generation |
| `CHANGE_TIM` | MENU_TIME | — | TIMS | 6 | 0 | Time when the menu was generated last |
| `CHANGE_TMP` | RSTIMESTMP | — | DEC | 15 | 0 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| `ATTRIBUTES` | MENU_ATTR | — | CHAR | 10 | 0 | Attributes of the menu |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | AGR_DEFINE | MANDT | T000 |  | |
| `PARENT_AGR` | AGR_DEFINE | MANDT | AGR_DEFINE |  | |
| `PARENT_AGR` | AGR_DEFINE | PARENT_AGR | AGR_DEFINE |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_role_set_masterlang.txt`
- `zbacbe062.txt`
- `zbacbe064.txt`
- `zbacbe065.txt`
- `zisfi0166.txt`
- `zissecrev.txt`
- `zmmpre030s.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
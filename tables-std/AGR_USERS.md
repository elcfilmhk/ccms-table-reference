# `AGR_USERS`

**Description:** Authorization Group Users — role assignments
**Category:** Standard SAP Table
**References:** 14 SELECT statements across 12 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/agr_users/) — validated 2026-05-30, schema v1.0
**Schema fields:** 6 fields | **Data types:** CHAR(3), DATS(1), DEC(1), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `EXCLUDE` | AGR_EXCL | — | CHAR | 1 | 0 | Exclusive |
| `CHANGE_DAT` | MENU_DATE | — | DATS | 8 | 0 | Date of menu generation |
| `CHANGE_TIM` | MENU_TIME | — | TIMS | 6 | 0 | Time when the menu was generated last |
| `CHANGE_TST` | RSTIMESTMP | — | DEC | 15 | 0 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| `ORG_FLAG` | AGR_ORG | — | CHAR | 1 | 0 | Flag: Assignment Comes From HR Organization Management |
| `COL_FLAG` | AGR_COL | — | CHAR | 1 | 0 | Flag: Assignment from composite role |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AGR_NAME` | AGR_USERS | MANDT | AGR_DEFINE |  | |
| `AGR_NAME` | AGR_USERS | AGR_NAME | AGR_DEFINE |  | |
| `MANDT` | AGR_USERS | MANDT | T000 |  | |
| `UNAME` | AGR_USERS | MANDT | USR02 |  | |
| `UNAME` | AGR_USERS | UNAME | USR02 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe002.txt`
- `zbacbe034.txt`
- `zbacbe061.txt`
- `zbacbe062.txt`
- `zbacbe063.txt`
- `zbacbe064.txt`
- `zbacbe065.txt`
- `zbacbei04.txt`
- `ziscs0004f01.txt`
- `zisfi0166.txt`
- `zissecrev.txt`
- `zmmpre030s.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
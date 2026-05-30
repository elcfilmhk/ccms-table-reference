# `EITR`

**Description:** Technical Installation — technical location assignment
**Category:** Standard SAP Table
**References:** 6 SELECT statements across 5 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eitr/) — validated 2026-05-30, schema v1.0
**Schema fields:** 12 fields | **Data types:** CHAR(11), DATS(1)

## Key Fields
`BUKRS` | `VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `PORTION` | PORTION | TE420 | CHAR | 8 | 0 | Portion |
| `GPARTNER` | BU_PARTNER | BUT000 | CHAR | 10 | 0 | Business Partner Number |
| `VKONT` | VKONT_KK | FKKVK | CHAR | 12 | 0 | Contract Account Number |
| `ABWVK` | ABWVK_KK | FKKVK | CHAR | 12 | 0 | Alternative contract account for collective bills |
| `ABRVORG` | ABRVORG | — | CHAR | 2 | 0 | Billing Transaction |
| `VERTRAG` | VERTRAG | EVER | CHAR | 10 | 0 | Contract |
| `SPARTE` | SPARTE | TSPA | CHAR | 2 | 0 | Division |
| `MANOUTSORT` | MANOUTSORT | TE127 | CHAR | 8 | 0 | Reason for manual outsorting in billing |
| `SIMULATION` | SIMULATION | — | CHAR | 2 | 0 | Indicator: billing simulation |
| `TOBRELEASD` | TOBRELEASD | — | CHAR | 1 | 0 | Indicator: document not released yet |
| `FAEDN` | FAEDN_KK | — | DATS | 8 | 0 | Due date for net payment |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABWVK` | EITR | MANDT | FKKVK |  | |
| `ABWVK` | EITR | ABWVK | FKKVK |  | |
| `BUKRS` | EITR | MANDT | T001 |  | |
| `BUKRS` | EITR | BUKRS | T001 |  | |
| `GPARTNER` | EITR | MANDT | BUT000 |  | |
| `GPARTNER` | EITR | GPARTNER | BUT000 |  | |
| `MANDT` | EITR | MANDT | T000 |  | |
| `MANOUTSORT` | EITR | MANDT | TE127 |  | |
| `MANOUTSORT` | EITR | MANOUTSORT | TE127 |  | |
| `PORTION` | EITR | MANDT | TE420 |  | |
| `PORTION` | EITR | PORTION | TE420 |  | |
| `SPARTE` | EITR | SPARTE | TSPA |  | |
| `SPARTE` | EITR | MANDT | TSPA |  | |
| `VERTRAG` | EITR | MANDT | EVER |  | |
| `VERTRAG` | EITR | VERTRAG | EVER |  | |
| `VKONT` | EITR | MANDT | FKKVK |  | |
| `VKONT` | EITR | VKONT | FKKVK |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0027.txt`
- `zisbi0045.txt`
- `zisbi0048.txt`
- `zisbi0091.txt`
- `zisbifixeitr.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
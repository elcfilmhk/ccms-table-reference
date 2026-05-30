# `DFKKZPT`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 1 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkzpt/) — validated 2026-05-30, schema v1.0
**Schema fields:** 14 fields | **Data types:** CHAR(11), CURR(2), DATS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BETRK` | BETRK_KK | — | CURR | 13 | 2 | Assigned Amount in Transaction Currency |
| `BETRL` | BETRL_KK | — | CURR | 13 | 2 | Clarified Amount In Local Currency |
| `XAKON` | XAKON_KK | — | CHAR | 1 | 0 | Post Payment on Account |
| `KLAEB` | KLAEB_KK | — | CHAR | 12 | 0 | Number of Clarification Document |
| `KLAED` | KLAED_KK | — | DATS | 8 | 0 | Posting date of clarif. doc |
| `NRZAA` | NRZAA_KK | — | CHAR | 10 | 0 | Repayment request |
| `REPYM` | REPYM_KK | TFK042Z | CHAR | 1 | 0 | Payment Method for Repayment |
| `KUKON` | KUKON_KK | TFK020K | CHAR | 4 | 0 | Short Account Assignment for Transfer Postings |
| `RUEBL` | RUEBL_KK | — | CHAR | 12 | 0 | Number of the resetting document |
| `RUEAR` | RUEAR_KK | — | CHAR | 1 | 0 | Type of resetting document |
| `TXTRZ` | TXTRZ_KK | — | CHAR | 50 | 0 | Text For Payment on Account, Repayment, or Transfer Posting |
| `RUEZU` | RUEZU_KK | — | CHAR | 12 | 0 | Number of Reset Document |
| `HZUON` | HZUON_KK | — | CHAR | 18 | 0 | Assignment Number in G/L Document |
| `KLAEO` | KLAEH_KK | — | CHAR | 10 | 0 | Clarification Account |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `KUKON` | DFKKZPT | MANDT | TFK020K |  | |
| `KUKON` | DFKKZPT | KUKON | TFK020K |  | |
| `REPYM` | DFKKZPT | MANDT | TFK042Z |  | |
| `REPYM` | T001 | LAND1 | TFK042Z |  | |
| `REPYM` | DFKKZPT | REPYM | TFK042Z |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisfi_pylot_del.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
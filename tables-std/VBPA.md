# `VBPA`

**Description:** Sales Document Partner — partner addresses
**Category:** Standard SAP Table
**References:** 99 SELECT statements across 5 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbpa/) — validated 2026-05-30, schema v1.0
**Schema fields:** 21 fields | **Data types:** CHAR(17), NUMC(4)

## Key Fields
`KUNNR` | `LIFNR` | `PERNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KUNNR` | KUNNR | KNA1 | CHAR | 10 | 0 | Customer Number |
| `LIFNR` | LIFNR | LFA1 | CHAR | 10 | 0 | Account Number of Vendor or Creditor |
| `PERNR` | PERNR_D | — | NUMC | 8 | 0 | Personnel Number |
| `PARNR` | PARNR | — | NUMC | 10 | 0 | Number of contact person |
| `ADRNR` | ADRNR | — | CHAR | 10 | 0 | Address |
| `ABLAD` | ABLAD | — | CHAR | 25 | 0 | Unloading Point |
| `LAND1` | LAND1 | T005 | CHAR | 3 | 0 | Country Key |
| `ADRDA` | ADRDA | — | CHAR | 1 | 0 | Address indicator |
| `XCPDK` | XCPDK | — | CHAR | 1 | 0 | Indicator: Is the account a one-time account? |
| `HITYP` | HITYP_KH | THIT | CHAR | 1 | 0 | Customer hierarchy type |
| `PRFRE` | PRFRE | — | CHAR | 1 | 0 | Relevant for price determination ID |
| `BOKRE` | BOKRE | — | CHAR | 1 | 0 | Indicator: Customer Is Rebate-Relevant |
| `HISTUNR` | HISTUNR | — | NUMC | 2 | 0 | Level number within hierarchy |
| `KNREF` | KNREF | — | CHAR | 30 | 0 | Customer description of partner (plant, storage location) |
| `LZONE` | LZONE | — | CHAR | 10 | 0 | Transportation zone to or from which the goods are delivered |
| `HZUOR` | HZUOR | — | NUMC | 2 | 0 | Assignment to Hierarchy |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `PARVW_FF` | PARTNER_FF | — | CHAR | 1 | 0 | Indicator &#039;further partners in this function&#039; (VBPA2) |
| `ADRNP` | AD_PERSNUM | ADRP | CHAR | 10 | 0 | Person number |
| `KALE` | KALE | — | CHAR | 1 | 0 | Maintain appointments in calendar |
| `OIPBL` | OIF_PBLNRP | OIFSPBL | CHAR | 10 | 0 | Business location identifier (IS-Oil MRN) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADRNP` | VBPA | MANDT | ADRP |  | |
| `ADRNP` | VBPA | ADRNP | ADRP |  | |
| `ADRNP` | * |  | ADRP |  | |
| `ADRNP` | * |  | ADRP |  | |
| `HITYP` | VBPA | MANDT | THIT |  | |
| `HITYP` | VBPA | HITYP | THIT |  | |
| `KUNNR` | VBPA | MANDT | KNA1 |  | |
| `KUNNR` | VBPA | KUNNR | KNA1 |  | |
| `LAND1` | VBPA | MANDT | T005 |  | |
| `LAND1` | VBPA | LAND1 | T005 |  | |
| `LIFNR` | VBPA | MANDT | LFA1 |  | |
| `LIFNR` | VBPA | LIFNR | LFA1 |  | |
| `MANDT` | VBPA | MANDT | T000 |  | |
| `OIPBL` | VBPA | MANDT | OIFSPBL |  | |
| `OIPBL` | VBPA | OIPBL | OIFSPBL |  | |
| `PARVW` | VBPA | PARVW | TPAR |  | |
| `PARVW` | VBPA | MANDT | TPAR |  | |
| `POSNR` | VBPA | MANDT | VBUP |  | |
| `POSNR` | VBPA | VBELN | VBUP |  | |
| `POSNR` | VBPA | POSNR | VBUP |  | |
| `VBELN` | VBPA | MANDT | VBUK |  | |
| `VBELN` | VBPA | VBELN | VBUK |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `kunnr`, `parvw`, `vbeln`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00100.txt`
- `zissd00101.txt`
- `zsdisn001.txt`
- `zsdsodl02.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
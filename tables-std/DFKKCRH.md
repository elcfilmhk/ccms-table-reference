# `DFKKCRH`

**Description:** Credit Management History — credit limit history
**Category:** Standard SAP Table
**References:** 14 SELECT statements across 11 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkcrh/) — validated 2026-05-30, schema v1.0
**Schema fields:** 23 fields | **Data types:** CHAR(2), DATS(4), NUMC(17)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BON01` | BON01_KK | — | NUMC | 4 | 0 | Creditw. no. for January |
| `BON02` | BON02_KK | — | NUMC | 4 | 0 | Creditworthiness number for February |
| `BON03` | BON03_KK | — | NUMC | 4 | 0 | Creditworthiness number for March |
| `BON04` | BON04_KK | — | NUMC | 4 | 0 | Creditworthiness number for April |
| `BON05` | BON05_KK | — | NUMC | 4 | 0 | Creditworthiness number for May |
| `BON06` | BON06_KK | — | NUMC | 4 | 0 | Creditw. no. for June |
| `BON07` | BON07_KK | — | NUMC | 4 | 0 | Creditw.no. for July |
| `BON08` | BON08_KK | — | NUMC | 4 | 0 | Creditw.no. for August |
| `BON09` | BON09_KK | — | NUMC | 4 | 0 | Creditw.no. for September |
| `BON10` | BON10_KK | — | NUMC | 4 | 0 | Creditw.no. for October |
| `BON11` | BON11_KK | — | NUMC | 4 | 0 | Creditw.no. for November |
| `BON12` | BON12_KK | — | NUMC | 4 | 0 | Creditworthiness number for December |
| `BONMA` | BONMA_KK | — | NUMC | 4 | 0 | Manual Creditworthiness |
| `BONVH` | BONVH_KK | — | NUMC | 3 | 0 | Creditworthiness factor as a percentage |
| `BMADT` | BMADT_KK | — | DATS | 8 | 0 | Date On Which Creditworthiness Was Manually Set |
| `LFDNR` | BNLFN_KK | — | NUMC | 6 | 0 | Sequential Number Of a Creditworthiness Entry |
| `BONFR` | BONFR_KK | — | NUMC | 4 | 0 | Fixed Creditworthiness |
| `BFRDT` | BFRDT_KK | — | DATS | 8 | 0 | Date on Which Creditworthiness was Fixed |
| `BRLDT` | BRLDT_KK | — | DATS | 8 | 0 | Release Date of Fixed Creditworthiness |
| `BNEXT` | BNEXT_KK | — | NUMC | 4 | 0 | Value of External Creditworthiness Valuation |
| `BEXDT` | BEXDT_KK | — | DATS | 8 | 0 | Date of Last Change to Rating |
| `BCMTF` | BCMTF_KK | — | CHAR | 1 | 0 | FI-CA Score Must Be Replicated to SAP Credit Management |
| `BONTF` | BONTF_KK | — | CHAR | 4 | 0 | FI-CA Creditworthiness Last Replicated to Credit Management |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zficfdl04.txt`
- `ziscs0088.txt`
- `zisdm0104.txt`
- `zisdm0136.txt`
- `zisdm0136a.txt`
- `zisdm0136b.txt`
- `zisdm0136c.txt`
- `zisdm0136d.txt`
- `zisfi0025.txt`
- `zisfi0097.txt`
- `zisfi0131.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
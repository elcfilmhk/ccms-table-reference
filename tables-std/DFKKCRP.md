# `DFKKCRP`

**Description:** Credit Management — credit limit info
**Category:** Standard SAP Table
**References:** 14 SELECT statements across 9 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkcrp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 16 fields | **Data types:** CHAR(10), DATS(3), NUMC(2), TIMS(1)

## Key Fields
`VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `HERKF` | BHRKF_KK | — | CHAR | 2 | 0 | Origin of entry related to creditworthiness |
| `DATUM` | DATUM | — | DATS | 8 | 0 | Date |
| `BONIT` | BONIT_KK | — | NUMC | 4 | 0 | Creditworthiness |
| `VKONT` | VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `LAUFD` | LAUFD_KK | — | DATS | 8 | 0 | Date ID |
| `LAUFI` | LAUFI_KK | — | CHAR | 6 | 0 | Additional Identification Characteristic |
| `MAZAE` | MAZAE_KK | — | NUMC | 6 | 0 | Counter for several dunning notices to a business partner |
| `RLBEL` | RLBEL_KK | — | CHAR | 12 | 0 | Number of the return document |
| `BNARG` | BNARG_KK | — | CHAR | 30 | 0 | Key field of application |
| `XBSTO` | XBSTO_KK | — | CHAR | 1 | 0 | Creditworthiness Entry Was Reversed |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `CPUTM` | CPUTM | — | TIMS | 6 | 0 | Time of Entry |
| `XNEGB` | XNEGB_KK | — | CHAR | 1 | 0 | Creditworthiness Value is Negative |
| `DOCCRP` | DOCCRP_KK | — | CHAR | 32 | 0 | Reference for Manual Creditworthiness Entry |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zis_fi_calculate_cw.txt`
- `zisdm0104.txt`
- `zisfi0025.txt`
- `zisfi0088.txt`
- `zisfi0097.txt`
- `zisfi0101.txt`
- `zisfi0131.txt`
- `zisfi0147.txt`
- `zisfi0150.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
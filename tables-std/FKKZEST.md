# `FKKZEST`

**Description:** Billing Index Summary — billing summary by CA
**Category:** Standard SAP Table
**References:** 412 SELECT statements across 15 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkkzest/) — validated 2026-05-30, schema v1.0
**Schema fields:** 11 fields | **Data types:** CHAR(4), DATS(1), INT4(4), NUMC(1), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `FNAME` | FNAMEZE_KK | — | CHAR | 250 | 0 | File name (payment lot transfer) |
| `UNAME` | UNAME | — | CHAR | 12 | 0 | User Name |
| `DATUM` | DATUMW | — | DATS | 8 | 0 | Date |
| `UZEIT` | UZEIT | — | TIMS | 6 | 0 | Time |
| `ERRANZ` | ERRZE_KK | — | INT4 | 10 | 0 | Number of Errors in Payment Lot Transfer |
| `ECLUST` | ECLUST_KK | — | NUMC | 5 | 0 | Last Error Cluster |
| `ZSFIN` | SFIN_KK | — | INT4 | 10 | 0 | Last payment lot |
| `POSFIN` | PFIN_KK | — | INT4 | 10 | 0 | Last payment lot item |
| `LINFIN` | LFIN_KK | — | INT4 | 10 | 0 | Edited to Line |
| `XFIN` | XFINBI_KK | — | CHAR | 1 | 0 | File done |
| `XCLDEL` | XCLDEL_KK | — | CHAR | 1 | 0 | Cluster was deleted |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_zcazzintf.txt`
- `z_zcazzintf_rb.txt`
- `zcazzintf.txt`
- `zcazzintf_331.txt`
- `zcazzintf_new.txt`
- `zfiapc000.txt`
- `zisfi0003.txt`
- `zisfi0280.txt`
- `zisfi0311b_f01.txt`
- `zisfi0318_lcl.txt`
- `zrfkize03.txt`
- `zrfkize06.txt`
- `ztest1_zcazzintf.txt`
- `ztest2_zcazzintf.txt`
- `ztest_zcazzintf.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
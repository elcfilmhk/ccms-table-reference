# `DFKKRAPT`

**Description:** Payment Plan Installment — installment detail
**Category:** Standard SAP Table
**References:** 11 SELECT statements across 7 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkrapt/) — validated 2026-05-30, schema v1.0
**Schema fields:** 11 fields | **Data types:** CHAR(2), CUKY(3), CURR(4), DATS(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AUGDT` | AUGDT_KK | — | DATS | 8 | 0 | Clearing date |
| `AUGRD` | AUGRD_KK | — | CHAR | 2 | 0 | Clearing Reason |
| `AUGWA` | AUGWA_KK | — | CUKY | 5 | 0 | Clearing currency |
| `AUGBT` | AUGBT_KK | — | CURR | 13 | 2 | Clearing amount in clearing currency |
| `BETRH` | BETRH_KK | — | CURR | 13 | 2 | Amount In Local Currency With +/- Signs |
| `BETRW` | BETRW_KK | — | CURR | 13 | 2 | Amount in Transaction Currency with +/- Sign |
| `BUKRS` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `WAERS` | BLWAE_KK | — | CUKY | 5 | 0 | Transaction Currency |
| `STDAT` | STORDAT_KK | — | DATS | 8 | 0 | Reversal Document Posting Date |
| `PSWBT` | PSWBT_KK | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `PSWSL` | PSWSL_KK | — | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `STDAT`, `augbt`, `augdt`, `opbel`, `opupk`, `opupw`, `stdat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `opbel`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isbi_get_bill_invoice_docs.txt`
- `zisbi0040.txt`
- `zisbi0046.txt`
- `zisfi0028.txt`
- `zisfi0030.txt`
- `zisfi0037.txt`
- `zisfi0103.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
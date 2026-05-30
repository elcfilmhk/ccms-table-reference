# `ERCHC`

**Description:** Billing Document Line — line items for billing doc
**Category:** Standard SAP Table
**References:** 74 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/erchc/) — validated 2026-05-30, schema v1.0
**Schema fields:** 12 fields | **Data types:** CHAR(8), DATS(4)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `OPBEL` | E_PRINTDOC | — | CHAR | 12 | 0 | Number of print document |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `INTOPBEL` | INTOPBEL | — | CHAR | 12 | 0 | Number of Print Document Used to Reverse Document |
| `INTCPUDT` | INTCPUDT | — | DATS | 8 | 0 | Date on which invoicing reversal was entered |
| `INTBUDAT` | INTBUDAT | — | DATS | 8 | 0 | Posting date of invoicing reversal |
| `TOBRELEASD` | TOBRELEASD | — | CHAR | 1 | 0 | Indicator: document not released yet |
| `SIMULATED` | SIMULATED | — | CHAR | 1 | 0 | Indicator: invoicing generates a simulated document |
| `INVOICED` | INVOICED | — | CHAR | 1 | 0 | Indicator: document posted |
| `SPCANC` | SPCANC | — | CHAR | 1 | 0 | Adjustment Reversal |
| `STATUPD` | STATUPD | — | CHAR | 1 | 0 | Document Entered in Sales Statistics |
| `STATUPD_CANC` | STATUPD_CANC | — | CHAR | 1 | 0 | Reversal Document Entered in Sales Statistics |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `belnr`, `intbudat`, `intcpudt`, `intopbel`, `opbel`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `opbel`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_billpay_hist_date.txt`
- `z_isbi_get_bill_invoice_docs.txt`
- `zisbi0014.txt`
- `zisbi0014t.txt`
- `zisbi0026.txt`
- `zisbi0042.txt`
- `zisbi0046.txt`
- `zisbi0054.txt`
- `zisbi0057.txt`
- `zisbi0061.txt`
- `zisbi0080.txt`
- `zisbi0086.txt`
- `zisbi0110.txt`
- `zisbi0112.txt`
- `zisbi0226_f01.txt`
- `zisbi0250_form.txt`
- `zisbi_upd_bd.txt`
- `ziscs0084.txt`
- `ziscs0523_f01.txt`
- `zisfi0113_upd.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
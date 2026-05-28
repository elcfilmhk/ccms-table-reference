# `ERCHC`

**Description:** Billing Document Line — line items for billing doc
**Category:** Standard SAP Table
**References:** 74 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |

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

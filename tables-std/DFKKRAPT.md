# `DFKKRAPT`

**Description:** Payment Plan Installment — installment detail
**Category:** Standard SAP Table
**References:** 11 SELECT statements across 7 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |

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

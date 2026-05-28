# `ERDK`

**Description:** FI-CA Contract Document — financial contract document
**Category:** Standard SAP Table
**References:** 375 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BLDAT`, `BUDAT`, `DRUCKDAT`, `ERDAT`, `FICA_V`, `INTOPBEL`, `LOEVM`, `OPBEL`, `PARTNER`, `SIMULATED`, `STOKZ`, `VKONT`, `budat`, `erdat`, `fica_v`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BUDAT`, `ERDAT`, `OPBEL`, `budat`, `erdat`, `opbel`

## Join Paths
- `ERDK.OPBEL` → `DFKKKO.OPBEL` — FI-CA Doc → Doc Header

## Programs Using This Table
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `zisbi0006.txt`
- `zisbi0084.txt`
- `zisbi0086.txt`
- `zisbi0151.txt`
- `zisbi0201_tp.txt`
- `zisbi0219f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- `zisbi_invoice_preview_ss.txt`
- `ziscs0148.txt`
- `ziscs0151.txt`
- `ziscs_migration_bill_segment.txt`
- `zisfi0083.txt`
- `zisfi0083_1t.txt`
- `zisfi0116_test3.txt`
- `zisfi0138.txt`
- `zisfi0139.txt`
- `zisfi0207.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_

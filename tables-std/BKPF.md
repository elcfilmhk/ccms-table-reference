# `BKPF`

**Description:** Accounting Document Header — FI doc header
**Category:** Standard SAP Table
**References:** 29 SELECT statements across 11 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BUKRS` | | 🔑 | Primary key |
| `BELNR` | | 🔑 | Primary key |
| `GJAHR` | | 🔑 | Primary key |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
- `BKPF.BELNR` → `BSEG.BELNR` — FI Header → FI Line Item

## Programs Using This Table
- `zbacbe034.txt`
- `zfchzuord_2.txt`
- `zisfi0029.txt`
- `zisfi0043.txt`
- `zisfi0083.txt`
- `zisfi0083_1.txt`
- `zisfi0083_1t.txt`
- `zisfi0083_2.txt`
- `zisfi0090.txt`
- `zisfi0238_bw.txt`
- `zrepmir7.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_

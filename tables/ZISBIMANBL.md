# ZISBIMANBL
**Description:** Manual bill  configuration
**Total Fields:** 11
**Key Fields:** MANDT, TARIFTYP, TARIFART, BELZART, FL_COL

## Programs Using This Table
- `zisbi0027`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `TARIFART` | CHAR | 8 | 🔑 | Rate Type |
| 4 | `BELZART` | CHAR | 6 | 🔑 | Line Item Type |
| 5 | `FL_COL` | NUMC | 2 | 🔑 | Number of Columns |
| 6 | `PREIS` | CHAR | 10 |  | Price |
| 7 | `TARIFGRP` | CHAR | 8 |  | Set group |
| 8 | `TVORG_DR` | CHAR | 4 |  | Subtransaction for Document Item |
| 9 | `PR_FACTOR_DR` | DEC | 5 |  | Output factor |
| 10 | `TVORG_CR` | CHAR | 4 |  | Subtransaction for Document Item |
| 11 | `PR_FACTOR_CR` | DEC | 5 |  | Output factor |

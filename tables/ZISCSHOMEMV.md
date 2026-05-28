# ZISCSHOMEMV
**Description:** Home Move Customised table
**Total Fields:** 12
**Key Fields:** MANDT, MO_CA

## Programs Using This Table
- `ziscs0184`
- `ziscs0256`
- `ziscs0272`
- `zisfi0070`
- `zisfi0207`
- `zisucntrct`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MO_CA` | CHAR | 12 | 🔑 | Source CA |
| 3 | `MI_CA` | CHAR | 12 |  | Target CA |
| 4 | `STATUS` | CHAR | 1 |  | Home Move Status |
| 5 | `ACTION` | CHAR | 1 |  | Action |
| 6 | `TP_AMT` | CURR | 13 |  | Total Amount |
| 7 | `PRINT_DOC_F` | CHAR | 12 |  | Print Doc of final invoice |
| 8 | `PRINT_DOC_1` | CHAR | 12 |  | Print Doc of first invoice |
| 9 | `CREATED_ON` | CHAR | 14 |  | Created timestamp |
| 10 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 11 | `LAST_CHANGED_ON` | CHAR | 14 |  | Modified timestamp |
| 12 | `LAST_CHANGED_BY` | CHAR | 12 |  | Changed by |

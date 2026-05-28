# ZISMDVALIDSET1
**Description:** MDMS validation set assignment table
**Total Fields:** 8
**Key Fields:** MANDT, METERROLE, MSEH6, LOW_LIMIT, HIGH_LIMIT

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0023`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METERROLE` | CHAR | 50 | 🔑 | Meter Role |
| 3 | `MSEH6` | CHAR | 6 | 🔑 | External Unit of Measurement in Technical Format (6-Char.) |
| 4 | `LOW_LIMIT` | DEC | 17 | 🔑 | Threshold Low Limit |
| 5 | `HIGH_LIMIT` | DEC | 17 | 🔑 | Threshold High Limit |
| 6 | `VALIDSETID1` | CHAR | 50 |  | Validation Set ID 1 |
| 7 | `VALIDSETID2` | CHAR | 50 |  | Validation Set ID 2 |
| 8 | `VALIDSETID3` | CHAR | 50 |  | Validation Set ID 3 |

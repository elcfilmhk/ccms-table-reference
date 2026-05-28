# ZISMDVALIDSET
**Description:** Validation Set
**Total Fields:** 6
**Key Fields:** MANDT, METERROLE, MSEH6

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
| 4 | `VALIDSETID1` | CHAR | 50 |  | Validation Set ID 1 |
| 5 | `VALIDSETID2` | CHAR | 50 |  | Validation Set ID 2 |
| 6 | `VALIDSETID3` | CHAR | 50 |  | Validation Set ID 3 |

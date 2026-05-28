# ZISCSALLOWT
**Description:** Table for storing the temporary Staff Allowance
**Total Fields:** 3
**Key Fields:** MANDT, EMP_ID

## Programs Using This Table
- `ziscs0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMP_ID` | CHAR | 8 | 🔑 | Staff number |
| 3 | `EMP_ALLOW` | NUMC | 8 |  | Staff Allowance |

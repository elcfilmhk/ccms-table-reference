# ZISCSALLOW
**Description:** Table for storing the Staff Allowance
**Total Fields:** 6
**Key Fields:** MANDT, EMP_ID

## Programs Using This Table
- `zcctest41`
- `zisbi0066`
- `ziscs0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMP_ID` | CHAR | 8 | 🔑 | Staff number |
| 3 | `EMP_ALLOW` | NUMC | 8 |  | Staff Allowance |
| 4 | `INACTIVE` | CHAR | 1 |  | Inactive indicator |
| 5 | `PARENT_ID` | CHAR | 8 |  | Staff number |
| 6 | `CONTRACT_NO` | CHAR | 10 |  | Contract |

# ZISCSALLOWH
**Description:** History table for staff allowance
**Total Fields:** 10
**Key Fields:** MANDT, EMP_ID, SEQ_NO

## Programs Using This Table
- `zisbi0066`
- `ziscs0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMP_ID` | CHAR | 8 | 🔑 | Staff number |
| 3 | `SEQ_NO` | NUMC | 5 | 🔑 | &nbsp; |
| 4 | `ADATUM` | DATS | 8 |  | Last Changed On |
| 5 | `AZEIT` | TIMS | 6 |  | Time |
| 6 | `UNAME` | CHAR | 12 |  | User Name |
| 7 | `EMP_ALLOW` | NUMC | 8 |  | Staff Allowance |
| 8 | `INACTIVE` | CHAR | 1 |  | Inactive indicator |
| 9 | `PARENT_ID` | CHAR | 8 |  | Staff number |
| 10 | `CONTRACT_NO` | CHAR | 10 |  | Contract |

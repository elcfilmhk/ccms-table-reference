# ZISFIJOBID
**Description:** Job process in background
**Total Fields:** 9
**Key Fields:** MANDT, REPID, PID, NORMAL_BL, FINAL_BL

## Programs Using This Table
- `zisfi0113`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `NORMAL_BL` | CHAR | 1 | 🔑 | Boolean Variable (X=true, -=false, space=unknown) |
| 5 | `FINAL_BL` | CHAR | 1 | 🔑 | Boolean Variable (X=true, -=false, space=unknown) |
| 6 | `FR_VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `TO_VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `FR_DATE` | DATS | 8 |  | From Post Date |
| 9 | `TO_DATE` | DATS | 8 |  | To Post Date |

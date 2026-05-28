# ZISDMUNALLOCPOD
**Description:** Log of Automatic PoD Unallocation
**Total Fields:** 8
**Key Fields:** MANDT, REC_NO

## Programs Using This Table
- `zisdm0128`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REC_NO` | NUMC | 9 | 🔑 | Record Number |
| 3 | `POD_ID` | CHAR | 50 |  | Point of delivery ID |
| 4 | `DEVICE` | CHAR | 18 |  | Serial Number |
| 5 | `STATUS` | CHAR | 10 |  | Unallocation Status |
| 6 | `REASON` | CHAR | 100 |  | Failure Reason |
| 7 | `ACTVDATE` | DATS | 8 |  | Activity Date |
| 8 | `ACTNDATE` | DATS | 8 |  | Action Date |

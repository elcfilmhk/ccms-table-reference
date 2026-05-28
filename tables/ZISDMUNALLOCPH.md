# ZISDMUNALLOCPH
**Description:** Log of Automatic Profile Header Unallocation
**Total Fields:** 10
**Key Fields:** MANDT, REC_NO

## Programs Using This Table
- `zisdm0128`
- `zised0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REC_NO` | NUMC | 9 | 🔑 | Record Number |
| 3 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 4 | `DEVICE` | CHAR | 18 |  | Serial Number |
| 5 | `REGISTER` | NUMC | 3 |  | Register |
| 6 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 7 | `STATUS` | CHAR | 10 |  | Unallocation Status |
| 8 | `REASON` | CHAR | 100 |  | Failure Reason |
| 9 | `ACTVDATE` | DATS | 8 |  | Activity Date |
| 10 | `ACTNDATE` | DATS | 8 |  | Action Date |

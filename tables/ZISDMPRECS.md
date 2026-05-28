# ZISDMPRECS
**Description:** Custom table to handle P Records of Meter Reading Upload
**Total Fields:** 12
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdm0049`
- `zisdm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `ROUTEID` | CHAR | 8 |  | Route ID |
| 7 | `SCHDDATE` | DATS | 8 |  | System Date |
| 8 | `ELAPSEDTIME` | NUMC | 4 |  | Elapsed Time |
| 9 | `CONUMBER` | NUMC | 4 |  | Number of CO records |
| 10 | `MONUMBER` | NUMC | 4 |  | Number of MO records |
| 11 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 12 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

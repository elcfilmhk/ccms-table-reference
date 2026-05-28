# ZISDMGRECS
**Description:** Custom table to handle G Records of Meter Reading Upload
**Total Fields:** 14
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdh0024`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0103`
- `zisdm0142`
- `zisdm0407`
- `zisdm0409`
- `zisdm0411`
- `zrdm_dr_rep`
- `zrdm_us_rep`
- `zrdm_wd_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `ROUTEID` | CHAR | 8 |  | Route ID |
| 7 | `SCHDDATE` | DATS | 8 |  | Date |
| 8 | `CONUMBER` | CHAR | 4 |  | Number of Records |
| 9 | `MONUMBER` | CHAR | 4 |  | Number of Records |
| 10 | `RESEQUENCE` | CHAR | 1 |  | Resequence Flag |
| 11 | `ROUTEMSG` | CHAR | 80 |  | Route Message |
| 12 | `NEWNUMBER` | CHAR | 4 |  | Number of Records |
| 13 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 14 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

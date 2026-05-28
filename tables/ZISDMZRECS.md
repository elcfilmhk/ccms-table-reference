# ZISDMZRECS
**Description:** Custom table to handle P Records of Meter Reading Upload
**Total Fields:** 13
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
| 6 | `CREATETIME` | TIMS | 6 |  | System Time |
| 7 | `CREATEDATE` | DATS | 8 |  | System Date |
| 8 | `PCID` | CHAR | 6 |  | Additional Identification Characteristic |
| 9 | `ROUTEFILE` | NUMC | 4 |  | Route File number |
| 10 | `COFILE` | NUMC | 6 |  | CO File number |
| 11 | `MOFILE` | NUMC | 6 |  | MO File number |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 13 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

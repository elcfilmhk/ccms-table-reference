# ZISDMXRECS
**Description:** Custom table to handle X Records of Meter Reading Upload
**Total Fields:** 10
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
| 6 | `SERNUM` | CHAR | 14 |  | Meter Number |
| 7 | `TOUMODEL` | CHAR | 2 |  | TOU ITRON Meter Model - Default 'O' |
| 8 | `ZZRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 9 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 10 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

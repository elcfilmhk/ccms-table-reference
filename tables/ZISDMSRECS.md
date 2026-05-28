# ZISDMSRECS
**Description:** Custom table to handle S Records of Meter Reading Upload
**Total Fields:** 13
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdm0049`
- `zisdm0050`
- `zisdm0142`
- `zisdm0143`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `CHANGECODE1` | CHAR | 2 |  | Changed Note Indicator |
| 7 | `CHANGECODE2` | CHAR | 2 |  | Changed Note Indicator |
| 8 | `CHANGECODE3` | CHAR | 2 |  | Changed Note Indicator |
| 9 | `NEWMETER` | CHAR | 14 |  | Meter Number |
| 10 | `NEWMETERTYPE` | CHAR | 1 |  | Basic device category |
| 11 | `NEWSERVICETYPE` | CHAR | 1 |  | Basic device category |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 13 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

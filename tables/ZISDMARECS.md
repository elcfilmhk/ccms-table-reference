# ZISDMARECS
**Description:** Custom table to handle A Records of Meter Reading Upload
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
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 8 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 9 | `METERNUMBER` | CHAR | 14 |  | Meter Number |
| 10 | `ACTIONTYPE` | CHAR | 2 |  | Action Type Code |
| 11 | `ACTIONSTATUS` | CHAR | 2 |  | Status of Action to be taken |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 13 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

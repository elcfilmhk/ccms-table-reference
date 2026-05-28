# ZISDMTRECS
**Description:** Custom table to handle T Records of Meter Reading Upload
**Total Fields:** 12
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0143`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `REGCODE` | CHAR | 2 |  | Register Code |
| 7 | `NEWNUMBER` | NUMC | 2 |  | Number of INTEGER |
| 8 | `NEWDECIMALS` | NUMC | 1 |  | Number of DECIMALS |
| 9 | `LENGTH` | NUMC | 4 |  | Length of Data |
| 10 | `TOUDATA` | CHAR | 225 |  | TOU Data |
| 11 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 12 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

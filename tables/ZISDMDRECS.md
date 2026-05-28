# ZISDMDRECS
**Description:** Custom table to handle D Records of Meter Reading Upload
**Total Fields:** 10
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdh0024`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `DATACHANGE` | CHAR | 1 |  | Changed Note Indicator |
| 7 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 8 | `DATA` | CHAR | 120 |  | Short text |
| 9 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 10 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

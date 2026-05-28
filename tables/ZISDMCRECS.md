# ZISDMCRECS
**Description:** Custom table to handle C Records of Meter Reading Upload
**Total Fields:** 15
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
- `zisdm0143`
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
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 8 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 9 | `METERNUM` | CHAR | 4 |  | Number of Records |
| 10 | `RATECAT` | CHAR | 2 |  | Streetwise - Rate Category |
| 11 | `NEWSERVICE` | CHAR | 1 |  | New Service Indicator |
| 12 | `CHANGEDNOTE` | CHAR | 1 |  | Changed Note Indicator |
| 13 | `NOTETXT` | CHAR | 80 |  | Note Text |
| 14 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 15 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

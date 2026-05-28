# ZISDMTOUADJJOB_R
**Description:** TOU billing device MR adjustment Error Reading
**Total Fields:** 16
**Key Fields:** MANDT, ANLAGE, SERNR, ADATSOLL, ABLBELNR

## Programs Using This Table
- `zisdm0235`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 5 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `ADATSOLL_EABL` | DATS | 8 |  | Scheduled meter reading date |
| 8 | `ABLHINW` | CHAR | 4 |  | Note from meter reader |
| 9 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 10 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 11 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 12 | `ORG_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 13 | `REV_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 14 | `ORG_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 15 | `REV_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 16 | `RDG_NOCHG_IND` | CHAR | 1 |  | Reading no change indicator |

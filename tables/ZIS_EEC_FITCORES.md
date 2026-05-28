# ZIS_EEC_FITCORES
**Description:** FiT Correspondence History
**Total Fields:** 13
**Key Fields:** MANDT, RE_APP_NO, CDATE, CTIME

## Programs Using This Table
- `ziscrm0318`
- `ziscs0490`
- `ziscs0507`
- `ziscs0514`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `CDATE` | DATS | 8 | 🔑 | Created On |
| 4 | `CTIME` | TIMS | 6 | 🔑 | Time of Creation (to the Second) |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `COTYP` | CHAR | 4 |  | Correspondence Type |
| 7 | `UNAME` | CHAR | 12 |  | User Name |
| 8 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 9 | `LET_TYPE` | CHAR | 6 |  | Letter Type |
| 10 | `COM_MODE` | CHAR | 1 |  | Preferred Medium |
| 11 | `COM_LANG` | CHAR | 2 |  | Communication Language |
| 12 | `LET_LINK` | CHAR | 255 |  | Link of Letter |
| 13 | `STATUS` | CHAR | 3 |  | Status |

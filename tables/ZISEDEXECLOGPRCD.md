# ZISEDEXECLOGPRCD
**Description:** Execution Log for Profile Report by Calendar Days
**Total Fields:** 13
**Key Fields:** MANDT, RECID

## Programs Using This Table
- `zised0017`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RECID` | NUMC | 10 | 🔑 | Record ID for Execution Log |
| 3 | `ENQID` | NUMC | 9 |  | Execution Log Enquiry ID |
| 4 | `MULTIACC` | CHAR | 1 |  | Multi. Account |
| 5 | `MULTIPER` | CHAR | 1 |  | Multi. Period |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `DATEFROM` | DATS | 8 |  | Period from-date |
| 8 | `DATETO` | DATS | 8 |  | Period to-date |
| 9 | `SELECTEDDAYS` | NUMC | 4 |  | Selected Days |
| 10 | `USERID` | CHAR | 12 |  | User ID |
| 11 | `USERNAME` | CHAR | 40 |  | User Name |
| 12 | `ENQDATE` | DATS | 8 |  | Enquiry Date |
| 13 | `ENQTIME` | TIMS | 6 |  | Enquiry Time |

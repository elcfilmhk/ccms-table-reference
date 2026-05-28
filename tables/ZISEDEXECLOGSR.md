# ZISEDEXECLOGSR
**Description:** Execution Log for Profile Summation Report
**Total Fields:** 12
**Key Fields:** MANDT, RECID

## Programs Using This Table
- `zised0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RECID` | NUMC | 10 | 🔑 | Record ID for Execution Log |
| 3 | `ENQID` | NUMC | 9 |  | Execution Log Enquiry ID |
| 4 | `MULTIACC` | CHAR | 1 |  | Multi. Account |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `DATEFROM` | DATS | 8 |  | Period from-date |
| 7 | `DATETO` | DATS | 8 |  | Period to-date |
| 8 | `SELECTEDDAYS` | NUMC | 4 |  | Selected Days |
| 9 | `USERID` | CHAR | 12 |  | User ID |
| 10 | `USERNAME` | CHAR | 40 |  | User Name |
| 11 | `ENQDATE` | DATS | 8 |  | Enquiry Date |
| 12 | `ENQTIME` | TIMS | 6 |  | Enquiry Time |

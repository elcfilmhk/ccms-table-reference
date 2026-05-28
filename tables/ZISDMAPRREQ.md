# ZISDMAPRREQ
**Description:** Table used to store the approval metering reading data
**Total Fields:** 25
**Key Fields:** MANDT, ABLBELNR, APR_NO

## Programs Using This Table
- `zisdm0181`
- `zisdm0182`
- `zisdm0221`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `APR_NO` | NUMC | 4 | 🔑 | Current approval number |
| 4 | `GERNR` | CHAR | 18 |  | Device |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `ORI_RDG` | DEC | 31 |  | Original reading |
| 7 | `AMD_RDG` | DEC | 31 |  | Amend reading |
| 8 | `CONSUM` | DEC | 13 |  | Consumption limit |
| 9 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 10 | `ANLAGE` | CHAR | 10 |  | Installation |
| 11 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 12 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 13 | `REQ_NAME` | CHAR | 12 |  | Requestor |
| 14 | `REQ_DATE` | DATS | 8 |  | Request date |
| 15 | `REQ_TIME` | TIMS | 6 |  | Request Time |
| 16 | `REQ_STATUS` | CHAR | 4 |  | Request Status |
| 17 | `APR_NAME` | CHAR | 12 |  | Approver |
| 18 | `APR_REASON` | CHAR | 2 |  | Approval reason code |
| 19 | `APR_DATE` | DATS | 8 |  | Approval date |
| 20 | `APR_TIME` | TIMS | 6 |  | Approval time |
| 21 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 22 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 23 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 24 | `MASTER_SUB` | CHAR | 1 |  | Master-sub indicator |
| 25 | `REMARK` | CHAR | 50 |  | Remark |

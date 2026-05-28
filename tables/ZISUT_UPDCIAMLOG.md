# ZISUT_UPDCIAMLOG
**Description:** CIAM and CA update record
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, SENDT

## Programs Using This Table
- `ziscs1131`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SENDT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 5 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 6 | `CIAMID` | CHAR | 50 |  | CIAM ID |
| 7 | `TIMES` | NUMC | 3 |  | Update Times |
| 8 | `STATUS` | CHAR | 1 |  | Updating Status |
| 9 | `JOBTIMES` | NUMC | 3 |  | Number of JOB runs |
| 10 | `ERRORCODE` | CHAR | 10 |  | Error Code |
| 11 | `MESSAGE` | CHAR | 220 |  | Message Text |

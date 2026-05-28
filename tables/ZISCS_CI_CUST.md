# ZISCS_CI_CUST
**Description:** Event Batch ID Header
**Total Fields:** 18
**Key Fields:** MANDT, DRCUSTNO, EVENTNAME

## Programs Using This Table
- `ziscs_drevent_del`
- `zisdm0357`
- `zisdm0371`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250`
- `zisfi0304`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 4 | `LASTUPDATEDATE` | DATS | 8 |  | Last update date |
| 5 | `LASTUPDATETIME` | TIMS | 6 |  | Last update time |
| 6 | `LASTUPDATEBY` | CHAR | 12 |  | Last Update By |
| 7 | `ACTION` | CHAR | 1 |  | Action |
| 8 | `ACTIONBY` | CHAR | 12 |  | Action By |
| 9 | `ACTIONDATE` | DATS | 8 |  | Action Date |
| 10 | `ACTIONTIME` | TIMS | 6 |  | Action Time |
| 11 | `APPROVALLOTID` | CHAR | 10 |  | ADR Approval Lot ID |
| 12 | `BYPASS_APPR_IND` | CHAR | 1 |  | ADR Bypass Approval Indicator |
| 13 | `STATUS` | CHAR | 1 |  | Batch Status |
| 14 | `MAILING_NAME` | CHAR | 50 |  | Mailing Name |
| 15 | `MAILING_ADDR1` | CHAR | 100 |  | Mailing Address |
| 16 | `MAILING_ADDR2` | CHAR | 100 |  | Mailing Address |
| 17 | `MAILING_ADDR3` | CHAR | 100 |  | Mailing Address |
| 18 | `REMARKS` | CHAR | 80 |  | Remarks |

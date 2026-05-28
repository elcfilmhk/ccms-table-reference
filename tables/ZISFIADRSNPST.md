# ZISFIADRSNPST
**Description:** ADR Approval Snapshot
**Total Fields:** 14
**Key Fields:** MANDT, APPROVED_ON, APPROVED_TIME, EVENTNAME, EVENTDATE, STARTTIME, DRCUSTNO

## Programs Using This Table
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0304`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APPROVED_ON` | DATS | 8 | 🔑 | Approved On |
| 3 | `APPROVED_TIME` | TIMS | 6 | 🔑 | Approval Time |
| 4 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 5 | `EVENTDATE` | DATS | 8 | 🔑 | Event Date |
| 6 | `STARTTIME` | TIMS | 6 | 🔑 | Start Time |
| 7 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 8 | `APPROVALLOTID` | CHAR | 10 |  | ADR Approval Lot ID |
| 9 | `TOTAL_AMT` | DEC | 16 |  | Total Incentive Amount |
| 10 | `APPROVED_BY` | CHAR | 12 |  | Approved By |
| 11 | `BYPASS_APPR_IND` | CHAR | 1 |  | ADR Bypass Approval Indicator |
| 12 | `PAYEENAME` | CHAR | 80 |  | Payee Name |
| 13 | `PARTICIPATION` | CHAR | 1 |  | Y/N |
| 14 | `POSTING_IND` | CHAR | 1 |  | General Flag |

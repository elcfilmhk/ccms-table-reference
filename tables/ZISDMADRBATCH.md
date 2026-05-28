# ZISDMADRBATCH
**Description:** Event Batch ID Header
**Total Fields:** 17
**Key Fields:** MANDT, BATCHID

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisdm0356`
- `zisdm0357_backup`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0251`
- `zisfi0274`
- `zisfi0304`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHID` | CHAR | 80 | 🔑 | Batch ID |
| 3 | `LASTUPDATEDATE` | DATS | 8 |  | Last update date |
| 4 | `LASTUPDATETIME` | TIMS | 6 |  | Last update time |
| 5 | `LASTUPDATEBY` | CHAR | 12 |  | Last Update By |
| 6 | `ACTION` | CHAR | 1 |  | Action |
| 7 | `ACTIONBY` | CHAR | 12 |  | Action By |
| 8 | `ACTIONDATE` | DATS | 8 |  | Action Date |
| 9 | `ACTIONTIME` | TIMS | 6 |  | Action Time |
| 10 | `APPROVALLOTID` | CHAR | 10 |  | ADR Approval Lot ID |
| 11 | `BYPASS_APPR_IND` | CHAR | 1 |  | ADR Bypass Approval Indicator |
| 12 | `BATCHSTATUS` | CHAR | 1 |  | Batch Status |
| 13 | `MAILING_NAME` | CHAR | 50 |  | Mailing Name |
| 14 | `MAILING_ADDR1` | CHAR | 100 |  | Mailing Address |
| 15 | `MAILING_ADDR2` | CHAR | 100 |  | Mailing Address |
| 16 | `MAILING_ADDR3` | CHAR | 100 |  | Mailing Address |
| 17 | `REMARKS` | CHAR | 80 |  | Remarks |

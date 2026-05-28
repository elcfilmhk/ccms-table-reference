# ZISFIDDINT
**Description:** Direct Debit Change/Confirmation Input Interim table
**Total Fields:** 10
**Key Fields:** MANDT, BATCHDATE, RECTYPE, EXECTYPE, JOBNO, SEQNO

## Programs Using This Table
- `zisfi0018`
- `zisfi0072`
- `zisfi0072_new`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHDATE` | DATS | 8 | 🔑 | Date stamp |
| 3 | `RECTYPE` | CHAR | 1 | 🔑 | Record Type for Direct Debit Confirmation |
| 4 | `EXECTYPE` | CHAR | 4 | 🔑 | Interface control - function name |
| 5 | `JOBNO` | NUMC | 5 | 🔑 | Process ID |
| 6 | `SEQNO` | NUMC | 6 | 🔑 | Consecutive sequence number used for multiple records |
| 7 | `DATA` | CHAR | 255 |  | Context string |
| 8 | `FULL_CNT` | INT4 | 10 |  | Full  executed count |
| 9 | `OK_CNT` | INT4 | 10 |  | Record accepted count |
| 10 | `FAIL_CNT` | INT4 | 10 |  | Record failed count |

# ZISFIRECELE
**Description:** Daily collection reconciliation electricity RFI117
**Total Fields:** 13
**Key Fields:** CLIENT, BUDAT, PAYSR

## Programs Using This Table
- `zisfi0041`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting date |
| 3 | `PAYSR` | CHAR | 20 | 🔑 | Payment source |
| 4 | `INS_NO` | INT4 | 10 |  | No. of payment transaction of Input source |
| 5 | `INS_AMT` | CURR | 13 |  | Input source |
| 6 | `COM_NO` | INT4 | 10 |  | No. of payment transaction of computed |
| 7 | `COM_AMT` | CURR | 13 |  | Computed amount |
| 8 | `DIF_NO` | INT4 | 10 |  | No. of payment transaction of Different |
| 9 | `DIF_AMT` | CURR | 13 |  | Different amount |
| 10 | `CCM_NO` | INT4 | 10 |  | No. of payment transaction of CCMS accepted |
| 11 | `CCM_AMT` | CURR | 13 |  | CCMS accepted amount |
| 12 | `DUM_NO` | INT4 | 10 |  | No. of payment transection of Dummy account |
| 13 | `DUM_AMT` | CURR | 13 |  | Dummy account amount |

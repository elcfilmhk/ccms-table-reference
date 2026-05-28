# ZMCOM_POINT_TRAN
**Description:** Eco-Domeo Point transactions sync status
**Total Fields:** 15
**Key Fields:** MANDT, TRANS_ID, VKONT

## Programs Using This Table
- `ziscs0492`
- `ziscs0493`
- `ziscs0494`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRANS_ID` | CHAR | 32 | 🔑 | EcoPoints Transaction ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `STATUS` | CHAR | 1 |  | Status of Transaction |
| 5 | `ERROR_CODE` | CHAR | 2 |  | Error Code |
| 6 | `TRANS_REAS` | CHAR | 50 |  | Eco Points Transaction Reason |
| 7 | `REF_NO` | CHAR | 80 |  | Reference ID |
| 8 | `TRANS_DATE` | DATS | 8 |  | Transaction Date |
| 9 | `TRANS_TIME` | TIMS | 6 |  | Transaction Time |
| 10 | `PROCESS_TIME` | TIMS | 6 |  | Processing Time |
| 11 | `DOMEO_POINTS` | INT4 | 10 |  | Domeo Point |
| 12 | `ECO_POINTS` | INT4 | 10 |  | Eco Point |
| 13 | `DOMEO_ID` | CHAR | 100 |  | Contact |
| 14 | `RETRY_COUNT` | NUMC | 2 |  | Retry Counter |
| 15 | `MESSAGE` | CHAR | 255 |  | Text, 255 Characters |

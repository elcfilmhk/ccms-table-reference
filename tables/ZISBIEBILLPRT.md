# ZISBIEBILLPRT
**Description:** E-Channel for dunning (Email)
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, CORR_TYPE, BILL_ID, ERDAT

## Programs Using This Table
- `zisbi0043`
- `zisbi0043n`
- `zisbi0090`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CORR_TYPE` | CHAR | 1 | 🔑 | Correspondence Type |
| 4 | `BILL_ID` | CHAR | 2 | 🔑 | Bill ID |
| 5 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 6 | `AUSDT` | DATS | 8 |  | Date of issue |
| 7 | `COPRI` | DATS | 8 |  | Print Date |

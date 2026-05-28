# ZISBIFAXPRINT
**Description:** Contract Account documents  to be faxed (E-Channel)
**Total Fields:** 10
**Key Fields:** MANDT, ERDAT, VKONT, CORR_TYPE, BILL_ID, DOCUMENT

## Programs Using This Table
- `zisbi0043`
- `zisbi0043n`
- `zisbi0084`
- `zisbi0085`
- `zisbi0090`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CORR_TYPE` | CHAR | 1 | 🔑 | Correspondence Type |
| 5 | `BILL_ID` | CHAR | 2 | 🔑 | Bill ID |
| 6 | `DOCUMENT` | CHAR | 12 | 🔑 | Document ID |
| 7 | `FAXPHONENO` | CHAR | 20 |  | Fax billing telephone number |
| 8 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 9 | `COPRI` | DATS | 8 |  | Print Date |
| 10 | `AUSDT` | DATS | 8 |  | Date of issue |

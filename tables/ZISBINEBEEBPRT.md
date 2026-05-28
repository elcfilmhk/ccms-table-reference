# ZISBINEBEEBPRT
**Description:** NEBE EBill Print Table
**Total Fields:** 8
**Key Fields:** MANDT, ERDAT, OPBEL

## Programs Using This Table
- `zisbi0116`
- `zisbi0117`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | NEBE document number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `CHARGE_TYPE` | CHAR | 3 |  | Charge type |
| 6 | `REF_NO` | CHAR | 20 |  | Reference no. |
| 7 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 8 | `DRUCKDAT` | DATS | 8 |  | Print Date |

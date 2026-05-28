# ZISBI_CA_OUTSORT
**Description:** Outsort CA for Invoicing
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, ERDAT, ERZEIT

## Programs Using This Table
- `zisbi0208`
- `zisbi0210`
- `zisbi0236`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 5 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 6 | `MANOUTS_IN` | CHAR | 8 |  | Reason for manual outsorting in invoicing |
| 7 | `STATUS` | CHAR | 1 |  | Update Status |
| 8 | `AENDT` | DATS | 8 |  | Date of last change |
| 9 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 10 | `ZTXT` | CHAR | 20 |  | Reference |

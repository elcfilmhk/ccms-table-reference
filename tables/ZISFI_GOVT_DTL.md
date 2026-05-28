# ZISFI_GOVT_DTL
**Description:** Government Subsidy Invoice details
**Total Fields:** 8
**Key Fields:** MANDT, RUNDT, BUDAT, VKONT, PRINTDOC, TRANPROC

## Programs Using This Table
- `zisfi0185`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `PRINTDOC` | CHAR | 12 | 🔑 | Number of print document |
| 6 | `TRANPROC` | CHAR | 12 | 🔑 | Transaction process |
| 7 | `SUBOFFAMT` | CURR | 13 |  | Subsidy offset amount |
| 8 | `SUBREVAMT` | CURR | 13 |  | Subsidy reverse amount |

# ZISFI_GOVT_DTL_S
**Description:** Government Subsidy Invoice details Separated by Scheme
**Total Fields:** 9
**Key Fields:** MANDT, RUNDT, BUDAT, VKONT, SCHEME, PRINTDOC, TRANPROC

## Programs Using This Table
- `zisfi0185`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 6 | `PRINTDOC` | CHAR | 12 | 🔑 | Number of print document |
| 7 | `TRANPROC` | CHAR | 12 | 🔑 | Transaction process |
| 8 | `SUBOFFAMT` | CURR | 13 |  | Subsidy offset amount |
| 9 | `SUBREVAMT` | CURR | 13 |  | Subsidy reverse amount |

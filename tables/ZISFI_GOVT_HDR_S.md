# ZISFI_GOVT_HDR_S
**Description:** Government Subsidy Invoice header Separated by Scheme
**Total Fields:** 7
**Key Fields:** MANDT, RUNDT, BUDAT, SCHEME

## Programs Using This Table
- `ziscs0225`
- `zisfi0185`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 5 | `SUBOFFAMT` | CURR | 13 |  | Subsidy offset amount |
| 6 | `SUBREVAMT` | CURR | 13 |  | Subsidy reverse amount |
| 7 | `NETAMT` | CURR | 13 |  | Net Subsidy amount |

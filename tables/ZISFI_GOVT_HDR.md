# ZISFI_GOVT_HDR
**Description:** Government Subsidy Invoice header
**Total Fields:** 6
**Key Fields:** MANDT, RUNDT, BUDAT

## Programs Using This Table
- `zisfi0185`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `SUBOFFAMT` | CURR | 13 |  | Subsidy offset amount |
| 5 | `SUBREVAMT` | CURR | 13 |  | Subsidy reverse amount |
| 6 | `NETAMT` | CURR | 13 |  | Net Subsidy amount |

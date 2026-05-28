# ZISFINEBECHRG
**Description:** Master data: NEBE items
**Total Fields:** 8
**Key Fields:** MANDT, HVORG, TVORG

## Programs Using This Table
- `zisfi0016`
- `zisfi0084`
- `zisfi0116`
- `zisfi0116_1`
- `zisfi0116_test`
- `zisfi0116_test2`
- `zisfi0116_test3`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `EVT_0300` | CHAR | 1 |  | 'X' = include, space = exclude |
| 5 | `EVT_R720` | CHAR | 1 |  | 'X' = include, space = exclude |
| 6 | `RFI01` | CHAR | 1 |  | 'X' = in report, space = in excel file |
| 7 | `RFI18A` | CHAR | 1 |  | 'X' = in report, space = in excel file |
| 8 | `RFI45` | CHAR | 1 |  | Section in RFI45 report (space = exclude) |

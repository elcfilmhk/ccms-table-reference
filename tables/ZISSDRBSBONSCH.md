# ZISSDRBSBONSCH
**Description:** Residential Bonus Scheme
**Total Fields:** 26
**Key Fields:** MANDT, SCHEME, BONSC, AB, BIS

## Programs Using This Table
- `zissd00074`
- `zissd00087`
- `zissd00112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME` | CHAR | 10 | 🔑 | Scheme |
| 3 | `BONSC` | CHAR | 10 | 🔑 | Scheme Type |
| 4 | `AB` | DATS | 8 | 🔑 | Valid from (main) |
| 5 | `BIS` | DATS | 8 | 🔑 | Valid to (main) |
| 6 | `ACTUAL_END` | DATS | 8 |  | Actual End Date for Promotion |
| 7 | `VLFRM` | DATS | 8 |  | Valid from (sub) |
| 8 | `VLTO` | DATS | 8 |  | Valid to (sub) |
| 9 | `TTLBN` | CURR | 13 |  | Total bonus amount |
| 10 | `FSTBN` | CURR | 13 |  | 1st bonus amount |
| 11 | `BONUS` | CURR | 13 |  | Bonus amount for each installment |
| 12 | `EWFLG` | CHAR | 1 |  | Bonus related to EWH |
| 13 | `ICFLG` | CHAR | 1 |  | Bonus related to IC |
| 14 | `SINGLE` | CHAR | 1 |  | Single Appliances |
| 15 | `SWFLG` | CHAR | 1 |  | Switching |
| 16 | `NMIFLG` | CHAR | 1 |  | New Move-In |
| 17 | `COM_FLAG` | CHAR | 1 |  | Connection Object for Main Scheme (main) |
| 18 | `GRADE_1_FLAG` | CHAR | 1 |  | Grade 1 Appliance |
| 19 | `QUOT` | CHAR | 10 |  | Quotation No. |
| 20 | `PRCHG` | CHAR | 200 |  | Product Description (Chinese) |
| 21 | `PRENG` | CHAR | 200 |  | Product Description (English) |
| 22 | `KWHIC` | CURR | 12 |  | KWH for IC |
| 23 | `KWHEWH` | CURR | 12 |  | KWH for EWH |
| 24 | `PRINT_FLAG` | CHAR | 1 |  | Print T & C Flag |
| 25 | `SCHEME_DESC_ENG` | CHAR | 60 |  | English Scheme description |
| 26 | `SCHEME_DESC_CHIN` | CHAR | 60 |  | Chinese Scheme description |

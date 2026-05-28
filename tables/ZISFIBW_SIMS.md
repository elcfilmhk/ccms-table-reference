# ZISFIBW_SIMS
**Description:** SMIS data extraction to BW
**Total Fields:** 17
**Key Fields:** MANDT, CPUDT, OPBEL, HKONT, AUGBL

## Programs Using This Table
- `zisfi0238_bw`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CPUDT` | DATS | 8 | 🔑 | Day On Which Accounting Document Was Entered |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 4 | `HKONT` | CHAR | 10 | 🔑 | General Ledger Account |
| 5 | `AUGBL` | CHAR | 12 | 🔑 | Clearing Document or Printed Document |
| 6 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 9 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 10 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 11 | `VBELN` | CHAR | 10 |  | Subsequent sales and distribution document |
| 12 | `OPTXT` | CHAR | 50 |  | Item text |
| 13 | `BLART` | CHAR | 2 |  | Document Type |
| 14 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 15 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 16 | `KOSTL` | CHAR | 10 |  | Cost Center |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |

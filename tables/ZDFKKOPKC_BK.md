# ZDFKKOPKC_BK
**Description:** Card Data Appendix for FICA Document (Masking Backup)
**Total Fields:** 10
**Key Fields:** MANDT, OPBEL, OPUPK

## Programs Using This Table
- `ziscvdatamskdatabackup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Payment Cards: Card Data |
| 5 | `CCINS` | CHAR | 4 |  | Payment card type |
| 6 | `CCNUM` | CHAR | 25 |  | Payment cards: Card number |
| 7 | `CCFOL` | CHAR | 10 |  | Payment cards: Payment card suffix |
| 8 | `DATAB` | DATS | 8 |  | Payment cards: Valid from |
| 9 | `DATBI` | DATS | 8 |  | Payment Cards: Valid To |
| 10 | `CCNAME` | CHAR | 40 |  | Payment cards: Name of cardholder |

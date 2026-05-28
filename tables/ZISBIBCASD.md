# ZISBIBCASD
**Description:** Backcharge Recovered Amount Custom Table
**Total Fields:** 11
**Key Fields:** MANDT, ZZREASON, ZZTARIFTYP, ZZOPBEL, ZZAUGDT

## Programs Using This Table
- `zisbi0040`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREASON` | CHAR | 100 | 🔑 | Text (100 characters) |
| 3 | `ZZTARIFTYP` | CHAR | 1 | 🔑 | Group for Rate categories |
| 4 | `ZZOPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 5 | `ZZAUGDT` | DATS | 8 | 🔑 | Clearing date |
| 6 | `ZZVKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `ZZRECOVERED` | CURR | 13 |  | Recovered Amount in clearing currency |
| 8 | `ZZALLOWANCE` | CURR | 13 |  | Recovered Amount in clearing currency |
| 9 | `ZZWAIVED` | CURR | 13 |  | Recovered Amount in clearing currency |
| 10 | `ZZINSTALL` | CHAR | 1 |  | Installment plan payment |
| 11 | `ZZWAERS` | CUKY | 5 |  | Transaction Currency |

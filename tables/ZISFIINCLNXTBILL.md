# ZISFIINCLNXTBILL
**Description:** Include next bill
**Total Fields:** 10
**Key Fields:** MANDT, SOURCE, ERDAT, ERZEIT, VERTRAG

## Programs Using This Table
- `ziscs0023`
- `ziscs0028`
- `ziscs0146`
- `ziscs0198`
- `ziscs0207`
- `ziscs0256`
- `ziscs0297`
- `zisfi0134`
- `zisfi0306`
- `zmoveindoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCE` | CHAR | 10 | 🔑 | Creation Source |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 5 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 8 | `ACTION` | CHAR | 1 |  | Action |
| 9 | `STATUS` | CHAR | 1 |  | Status |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |

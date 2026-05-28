# ZISFIDDCON
**Description:** Direct Debit Confirmation at Invoicing
**Total Fields:** 4
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisfi0072`
- `zisfi0072_new`
- `zisfi0076`
- `zisfifixdd`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DATES` | DATS | 8 |  | Batch run date for DD confirmation |
| 4 | `PROTECTED` | CHAR | 1 |  | Processing lock write-protected |

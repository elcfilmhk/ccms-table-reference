# ZISCSMIBIZAG
**Description:** MI automation Business Agreement error log
**Total Fields:** 6
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0256`
- `ziscs0270`
- `ziscs0297`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 4 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 5 | `NOT_COMPLETE` | CHAR | 1 |  | Single-Character Flag |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |

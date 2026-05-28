# ZISBI_REB_CONSUMPT
**Description:** Rebate Consumption
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0201`
- `zisbi0202`
- `zisbi0203`
- `zisbi0208`
- `zisbi0216`
- `zisbi0219`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 2 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 3 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 4 | `CONSUM` | DEC | 13 |  | Consumption consumed |
| 5 | `BILL_CONSUM` | DEC | 13 |  | Billed Consumption (KWH) |
| 6 | `ELIG_CONSUM` | DEC | 13 |  | Billed Consumption eligible for rebate |
| 7 | `BILL_MTHD` | CHAR | 3 |  | Billing method for last bill |
| 8 | `NO_BILL_DAYS` | DEC | 10 |  | Number of billing days |
| 9 | `NO_REB_DAYS` | DEC | 10 |  | Number of days in rebate period |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `STATTART` | CHAR | 8 |  | Rate type for statistical analysis |
| 12 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |

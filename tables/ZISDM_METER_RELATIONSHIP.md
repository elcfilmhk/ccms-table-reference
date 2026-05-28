# ZISDM_METER_RELATIONSHIP
**Description:** Relationship(s) under the meter
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0007_gprs`
- `ziscs0106`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 3 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 4 | `INDEXNR` | NUMC | 12 |  | Consecutive number of register relationship |
| 5 | `PRUEFGR` | CHAR | 4 |  | Validation group for dependent validations |
| 6 | `ZWZUART` | NUMC | 2 |  | Register relationship type |
| 7 | `ZWZUARTTXT` | CHAR | 30 |  | Text for register relationship type |
| 8 | `AUTOEND` | CHAR | 1 |  | Prorate register relationship automatically |
| 9 | `MAIN_SERNR` | CHAR | 18 |  | Serial Number |
| 10 | `CHECK_SERNR` | CHAR | 18 |  | Serial Number |

# ZISBIANNUAL_SUMMARY
**Description:** Annual Summary
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`
- `zcl_z_bapi_bill_pre_01_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONSUMPTION_MONTH` | CHAR | 20 |  | Char 20 |
| 2 | `ON_PEAK_KWH` | DEC | 31 |  | Billing quantity for internal billing format |
| 3 | `OFF_PEAK_KWH` | DEC | 31 |  | Billing quantity for internal billing format |
| 4 | `TOTAL_KWH` | DEC | 31 |  | Billing quantity for internal billing format |
| 5 | `ON_PEAK_KVA` | DEC | 16 |  | Entry value (installed value) for a device |
| 6 | `OFF_PEAK_KVA` | DEC | 16 |  | Entry value (installed value) for a device |
| 7 | `TOTAL_CHARGE` | CURR | 13 |  | Currency-dependent amount |
| 8 | `AVG_UNIT_RATE` | DEC | 31 |  | Billing quantity for internal billing format |
| 9 | `MTR_RDG_DATE` | CHAR | 20 |  | Char 20 |
| 10 | `NO_OF_DAYS` | INT4 | 10 |  | Whole Number with +/- Sign (-2.147.483.648 .. 2.147.483.647) |
| 11 | `AVG_KWH` | DEC | 31 |  | Billing quantity for internal billing format |

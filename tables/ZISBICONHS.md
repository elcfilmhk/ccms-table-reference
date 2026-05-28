# ZISBICONHS
**Description:** Consumption History
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zis_consumption_history=======ft`
- `ziscs0824`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZMONTH` | CHAR | 2 |  | Version Number Component |
| 2 | `ZYEAR` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 3 | `SDATE` | DATS | 8 |  | Field of type DATS |
| 4 | `TOTAL_CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 5 | `AVERAGE_CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 6 | `LAST_CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 7 | `PERC_RISE` | CURR | 13 |  | Percentage Increase of First Period |
| 8 | `BILL_TYPE` | CHAR | 1 |  | Single-Character Flag |
| 9 | `BILL_TYPE_NEW` | CHAR | 1 |  | Single-Character Flag |

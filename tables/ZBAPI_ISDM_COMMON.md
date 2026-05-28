# ZBAPI_ISDM_COMMON
**Description:** Common BAPI Fields
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `zbapi_iscs_acct_lp============ft`
- `zbapi_isdm_meter_lp===========ft`
- `zisdm0380`
- `zisdm0394`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `DATUM` | DATS | 8 |  | Date |
| 2 | `UZEIT` | TIMS | 6 |  | Time |
| 3 | `TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 4 | `DATETIME_C` | CHAR | 14 |  | Date Time in Character Type (YYYYMMDDhhmmss) |
| 5 | `VALUE_MODE` | CHAR | 1 |  | mode for month week day |
| 6 | `VALIDATED_READ` | CHAR | 1 |  | Single-Character Flag |
| 7 | `XFELD` | CHAR | 1 |  | Checkbox |

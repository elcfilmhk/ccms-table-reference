# ZDEPREQ
**Description:** Deposit requirement Type
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `z_calculate_deposit===========ft`
- `zisfi0045`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ANLAGE` | CHAR | 10 |  | Installation |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 5 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 6 | `DEPOSIT` | CURR | 13 |  | Currency-dependent amount |
| 7 | `TOTAL_CONS` | CURR | 13 |  | Currency-dependent amount |
| 8 | `HTYPE` | CHAR | 15 |  | Char 15 |
| 9 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 10 | `AVG_75` | CURR | 13 |  | Currency-dependent amount |
| 11 | `HIGH_60` | CURR | 13 |  | Currency-dependent amount |
| 12 | `REQ_DEPOSIT` | CURR | 13 |  | Currency-dependent amount |

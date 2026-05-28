# ZISDMACCON
**Description:** Structure for Actual consumption
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_actual_demand==========ft`
- `zisdatveri`
- `zisdm0017`
- `zisdm0090`
- `zisdm0091`
- `zisfi0031`
- `zisfi0043`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 5 | `ON_KVA` | DEC | 17 |  | Places before decimal point in billing quantity |
| 6 | `OFF_KVA` | DEC | 17 |  | Places before decimal point in billing quantity |
| 7 | `ON_KWH` | DEC | 17 |  | Places before decimal point in billing quantity |
| 8 | `OFF_KWH` | DEC | 17 |  | Places before decimal point in billing quantity |
| 9 | `TOT_KVAH` | DEC | 17 |  | Places before decimal point in billing quantity |
| 10 | `TOT_KWH` | DEC | 17 |  | Places before decimal point in billing quantity |
| 11 | `TOT_KVA` | DEC | 17 |  | Places before decimal point in billing quantity |
| 12 | `MAX_KVA` | DEC | 17 |  | Places before decimal point in billing quantity |
| 13 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 14 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 15 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |

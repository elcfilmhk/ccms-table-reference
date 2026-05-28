# ZISDMPROMR
**Description:** Customized structure for Processing Meter Reading
**Total Fields:** 19
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`
- `zisdm0150`
- `zisdm0156`
- `zisdm0170`
- `zisdm0236_sub`
- `zisdm0251`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `MATNR` | CHAR | 18 |  | Material Number |
| 4 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 5 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 6 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 7 | `CONSUMPT` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 8 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 9 | `ABLHINW` | CHAR | 4 |  | Note from meter reader |
| 10 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 11 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 12 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 13 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 14 | `UNTERDR` | CHAR | 1 |  | Suppression indicator |
| 15 | `DELETE_RESULT` | CHAR | 1 |  | Delete meter reading results |
| 16 | `FLAG` | CHAR | 1 |  | Correct / Error indicator |
| 17 | `REV_FLAG` | CHAR | 1 |  | Reversal Indicator |
| 18 | `SUBRC` | INT4 | 10 |  | Return Code |
| 19 | `ATIM` | CHAR | 4 |  | Meter reading time (relevant to billing) |

# ZISDMPROCMRO
**Description:** Structure for Process MRO data
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0050`
- `zisdm0051`
- `zisdm0086`
- `zisdm0137`
- `zisdm0152`
- `zisdm0170`
- `zisdm0254`
- `zisdm0260`
- `zisdm0297_sub`
- `zisdm0298_sub`
- `zisdm0317`
- `zisdm0344`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 3 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 4 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 5 | `UNTERDR` | CHAR | 1 |  | Suppression indicator |
| 6 | `DELETE_RESULT` | CHAR | 1 |  | Delete meter reading results |
| 7 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 8 | `ABLHINW` | CHAR | 4 |  | Note from meter reader |
| 9 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 10 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 11 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 12 | `ATIM` | CHAR | 4 |  | Meter reading time (relevant to billing) |
| 13 | `METERREADER` | CHAR | 3 |  | Meter reader number |

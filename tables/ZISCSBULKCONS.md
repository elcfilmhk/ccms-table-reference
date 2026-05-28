# ZISCSBULKCONS
**Description:** Structure for bulk consumption data
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bulk_consumption=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ONKWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 3 | `OFFKWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 4 | `ONKVA` | DEC | 16 |  | Entry value (installed value) for a device |
| 5 | `OFFKVA` | DEC | 16 |  | Entry value (installed value) for a device |
| 6 | `AVGKWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 7 | `AB` | DATS | 8 |  | Valid-From Date |
| 8 | `BIS` | DATS | 8 |  | Valid to date |

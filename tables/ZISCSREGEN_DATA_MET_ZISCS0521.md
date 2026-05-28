# ZISCSREGEN_DATA_MET_ZISCS0521
**Description:** Structure for RE Generation Data per Meter - ZISCS0521
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0519`
- `ziscs0521`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `START_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `EXPIRE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `METER_NUMBER` | CHAR | 18 |  | Device |
| 5 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 6 | `RE_TECHNOLOGY` | CHAR | 2 |  | RE Source |
| 7 | `LOCATION_ID` | CHAR | 10 |  | RE System Location |
| 8 | `KWH_TOTAL` | DEC | 31 |  | Profile value at application level |
| 9 | `COMM_START_DATE` | DATS | 8 |  | Commissioning Start Date |
| 10 | `COMM_END_DATE` | DATS | 8 |  | Commissioning End Date |

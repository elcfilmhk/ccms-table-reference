# ZISCSGENERATION_DATA_LOC
**Description:** Structure RE Generation Data Per Location
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0814`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `MODE` | CHAR | 1 |  | mode for month week day |
| 3 | `START_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EXPIRE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `LOCATION_ID` | CHAR | 10 |  | RE System Location |
| 6 | `LOCATION_DESC` | CHAR | 100 |  | RE System Location Name |
| 7 | `KWH_TOTAL` | DEC | 21 |  | AMI consumption value |
| 8 | `KWH_ONPEAK` | DEC | 21 |  | AMI consumption value |
| 9 | `KWH_SHOULDER` | DEC | 21 |  | AMI consumption value |
| 10 | `KWH_OFFPEAK` | DEC | 21 |  | AMI consumption value |
| 11 | `VALIDATE_STATUS` | CHAR | 4 |  | Status of profile value in interface |

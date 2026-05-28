# ZISCSGENERATION_DATA_MET
**Description:** Structure for RE Generation Data per Meter
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0508`
- `ziscs0510`
- `ziscs0521`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `MODE` | CHAR | 1 |  | mode for month week day |
| 3 | `START_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EXPIRE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `METER_NUMBER` | CHAR | 18 |  | Device |
| 6 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 7 | `RE_TECHNOLOGY` | CHAR | 2 |  | RE Source |
| 8 | `LOCATION_ID` | CHAR | 10 |  | RE System Location |
| 9 | `LOCATION_DESC` | CHAR | 100 |  | RE System Location Name |
| 10 | `KWH_TOTAL` | DEC | 21 |  | AMI consumption value |
| 11 | `KWH_ONPEAK` | DEC | 21 |  | AMI consumption value |
| 12 | `KWH_SHOULDER` | DEC | 21 |  | AMI consumption value |
| 13 | `KWH_OFFPEAK` | DEC | 21 |  | AMI consumption value |
| 14 | `VALIDATE_STATUS` | CHAR | 4 |  | Status of profile value in interface |

# ZISCSCONSUMPTION_DATA
**Description:** Consumption Data
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ztest_get_cons_01_mpc`
- `zcl_ztest_get_cons_03_mpc`
- `zcl_ztest_get_cons_mpc`
- `ziscs0711`
- `ziscs0734`
- `zisdm0337`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `MODE` | CHAR | 1 |  | mode for month week day |
| 3 | `START_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EXPIRE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `KWH_TOTAL` | DEC | 21 |  | AMI consumption value |
| 6 | `KWH_ONPEAK` | DEC | 21 |  | AMI consumption value |
| 7 | `KWH_SHOULDER` | DEC | 21 |  | AMI consumption value |
| 8 | `KWH_OFFPEAK` | DEC | 21 |  | AMI consumption value |
| 9 | `VALIDATE_STATUS` | CHAR | 4 |  | Status of profile value in interface |

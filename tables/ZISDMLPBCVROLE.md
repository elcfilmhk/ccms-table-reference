# ZISDMLPBCVROLE
**Description:** Conversion role for LP installation
**Total Fields:** 10
**Key Fields:** MANDT, METER_CONFIG, METER_ROLE, ZWNUMMER

## Programs Using This Table
- `zisdm0203`
- `zisdm0203_cbtolp`
- `zisdm0203_rbtolp`
- `zisdm0294`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METER_CONFIG` | CHAR | 10 | 🔑 | Meter Configuration |
| 3 | `METER_ROLE` | CHAR | 10 | 🔑 | The Meter Role to be converted to LP Biling |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `OLD_RATE_TYPE` | CHAR | 8 |  | Existing rate type of register of the device to be converted |
| 6 | `OLD_REL_FOR_BILL` | CHAR | 1 |  | Existing rel. for billing ind. of register of device convert |
| 7 | `NEW_RATE_TYPE` | CHAR | 8 |  | New rate type of the register of the device to be converted |
| 8 | `NEW_RATETYPE_GST` | CHAR | 8 |  | New rate type of register of the device to be convert (GST) |
| 9 | `NEW_REL_FOR_BILL` | CHAR | 1 |  | New rel. for billing ind. of register of device converted |
| 10 | `NEW_REL_FOR_BGST` | CHAR | 1 |  | New rel. for billing ind. of register of device convert(GST) |

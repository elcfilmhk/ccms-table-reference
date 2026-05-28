# ZISCS_ECO_CONS_LIST
**Description:** Output structure of FM "Z_BAPI_MULTI_ECODATA_CONS"
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_multi_ecodata_cons=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `P_ALERT_STATUS` | CHAR | 1 |  | Projected Alert Status |
| 3 | `U_ALERT_STATUS` | CHAR | 1 |  | Unusual Alert Status |
| 4 | `E_ALERT_STATUS` | CHAR | 1 |  | Bill Reminder Service |
| 5 | `PAY_ALERT_STATUS` | CHAR | 1 |  | Payment Reminder Service |
| 6 | `CONS_DEV` | CHAR | 10 |  | Consumption Deviation |
| 7 | `CURR_TEMP` | DEC | 12 |  | Current Tempreature |
| 8 | `CURR_HUM` | DEC | 12 |  | Current Humidity |

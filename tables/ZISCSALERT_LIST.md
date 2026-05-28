# ZISCSALERT_LIST
**Description:** Alert list for Set Consumption Alert BAPI
**Total Fields:** 7
**Key Fields:** VKONT, ALERT_TYPE, BLOCK_LEVEL

## Programs Using This Table
- `ziscrm0319`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 2 | `ALERT_TYPE` | CHAR | 2 | 🔑 | Alert Type |
| 3 | `BLOCK_LEVEL` | INT4 | 10 | 🔑 | Block Level |
| 4 | `SUBSCRIBED` | CHAR | 1 |  | Subscribed |
| 5 | `QUANTITY` | NUMC | 10 |  | Quantity |
| 6 | `AMOUNT` | CURR | 15 |  | Amount |
| 7 | `CHANGEDON` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |

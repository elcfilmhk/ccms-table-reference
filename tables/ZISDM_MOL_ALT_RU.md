# ZISDM_MOL_ALT_RU
**Description:** MOL Email Alert Table
**Total Fields:** 14
**Key Fields:** MANDT, VKONT, SERNR

## Programs Using This Table
- `zisdm0293`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `CAFLAG` | CHAR | 1 |  | Flag to select Contract Accounts |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `ALERT_TYPE` | CHAR | 1 |  | Email Alert Type |
| 8 | `ALERT_COMP` | CHAR | 1 |  | Email Alert Comparing Option |
| 9 | `ALERT_ADVICE` | CHAR | 1 |  | Monthly Saving Advice |
| 10 | `ALERT_MKVA` | NUMC | 8 |  | Max KVA |
| 11 | `ALERT_TKWH` | NUMC | 8 |  | Total kWh |
| 12 | `LAST_UPD_DATE` | DATS | 8 |  | Last Update Date |
| 13 | `LAST_UPD_TIME` | TIMS | 6 |  | Last Update Time |
| 14 | `LAST_UPD_BY` | CHAR | 50 |  | Last Update By |

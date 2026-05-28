# ZISSDECINST
**Description:** EC Installment Details
**Total Fields:** 16
**Key Fields:** MANDT, EC_ORDER_NO, EC_ORDER_ITEM, EC_INSTAL_NO, VKONT

## Programs Using This Table
- `zisfi0118`
- `zisfi0121`
- `zissd00065`
- `zissd00095`
- `zsdsodl05`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EC_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order Number |
| 3 | `EC_ORDER_ITEM` | NUMC | 6 | 🔑 | Sales Order Item Number |
| 4 | `EC_INSTAL_NO` | NUMC | 2 | 🔑 | EC Installment Number |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `EC_INSTAL_AMT` | CURR | 13 |  | EC Installment Amount |
| 7 | `EC_ACT_AMT_USED` | CURR | 13 |  | Actual EC Amount Used for Invoice |
| 8 | `EC_ACT_INV_DATE` | DATS | 8 |  | Actual Invoice Date |
| 9 | `EC_ACT_INV_TYPE` | CHAR | 1 |  | Actual Invoice Type |
| 10 | `EC_CF_AMT` | CURR | 13 |  | EC Carry Forward Amount |
| 11 | `EC_SCHD_READ_DAT` | DATS | 8 |  | Schedule Reading Date |
| 12 | `EC_UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 13 | `EC_UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 14 | `EC_UPDATE_BY` | CHAR | 12 |  | Name of person who changed object |
| 15 | `EC_REVISED_AMT` | CURR | 13 |  | Revised Amount |
| 16 | `EC_CF_AMT_OLD` | CURR | 13 |  | EC Carry Forward Amount |

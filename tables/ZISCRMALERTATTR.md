# ZISCRMALERTATTR
**Description:** Maintain Alert Attributes
**Total Fields:** 21
**Key Fields:** MANDT, ALERT_ID, CATEGORY, VALID_FROM, VALID_TO

## Programs Using This Table
- `zalertmsg`
- `ziscrm0023`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ALERT_ID` | CHAR | 20 | 🔑 | Alert Identifier |
| 3 | `CATEGORY` | CHAR | 2 | 🔑 | Alert Category |
| 4 | `VALID_FROM` | DATS | 8 | 🔑 | Alert Effective Date |
| 5 | `VALID_TO` | DATS | 8 | 🔑 | Alert Expiry Date |
| 6 | `CATEGORY_DESC` | CHAR | 16 |  | Alert Category Description |
| 7 | `STATIC_MESSAGE` | CHAR | 1 |  | Static Message Indicator |
| 8 | `SHORT_TEXT` | CHAR | 70 |  | Alert Message Short Text |
| 9 | `LONG_TEXT_1` | CHAR | 70 |  | Alert Message Long Text 1 |
| 10 | `LONG_TEXT_2` | CHAR | 70 |  | Alert Message Long Text 2 |
| 11 | `LONG_TEXT_3` | CHAR | 70 |  | Alert Message Long Text 3 |
| 12 | `POPUP` | CHAR | 1 |  | Popup Indicator |
| 13 | `LOG` | CHAR | 1 |  | Log Indicator |
| 14 | `CAT_PRIORITY` | NUMC | 2 |  | Category Display Priority |
| 15 | `SUB_CAT_PRIORITY` | NUMC | 2 |  | Sub-Category Display Priority |
| 16 | `CREATE_DATE` | DATS | 8 |  | Creation Date |
| 17 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 18 | `CREATE_BY` | CHAR | 12 |  | Created By |
| 19 | `CHANGE_DATE` | DATS | 8 |  | Changed Date |
| 20 | `CHANGE_TIME` | TIMS | 6 |  | Changed Time |
| 21 | `CHANGE_BY` | CHAR | 12 |  | Changed By |

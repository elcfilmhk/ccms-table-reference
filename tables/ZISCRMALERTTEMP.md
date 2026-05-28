# ZISCRMALERTTEMP
**Description:** Alert Message for Business Partner (Temp. Storage in CIC0)
**Total Fields:** 18
**Key Fields:** _none_

## Programs Using This Table
- `zalertmsg`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `BP` | CHAR | 10 |  | Business Partner Number |
| 3 | `CA` | CHAR | 12 |  | Contract Account Number |
| 4 | `ALERT_ID` | CHAR | 20 |  | Alert Identifier |
| 5 | `CATEGORY` | CHAR | 2 |  | Alert Category |
| 6 | `VALID_FROM` | DATS | 8 |  | Alert Effective Date |
| 7 | `VALID_TO` | DATS | 8 |  | Alert Expiry Date |
| 8 | `SEQ_NO` | NUMC | 6 |  | Alert Sequence Number |
| 9 | `CATEGORY_DESC` | CHAR | 16 |  | Alert Category Description |
| 10 | `CAT_PRIORITY` | NUMC | 2 |  | Category Display Priority |
| 11 | `SUB_CAT_PRIORITY` | NUMC | 2 |  | Sub-Category Display Priority |
| 12 | `SHORT_TEXT` | CHAR | 70 |  | Alert Message Short Text |
| 13 | `LONG_TEXT_1` | CHAR | 70 |  | Alert Message Long Text 1 |
| 14 | `LONG_TEXT_2` | CHAR | 70 |  | Alert Message Long Text 2 |
| 15 | `LONG_TEXT_3` | CHAR | 70 |  | Alert Message Long Text 3 |
| 16 | `CREATE_DATE` | DATS | 8 |  | Creation Date |
| 17 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 18 | `CREATE_BY` | CHAR | 12 |  | Created By |

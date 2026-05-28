# ZISFIBEA_REG
**Description:** FI BEA: Registeration
**Total Fields:** 17
**Key Fields:** MANDT, REGID, ITEM_NO

## Programs Using This Table
- `zisfi0254`
- `zisfi0256`
- `zisfi0294`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGID` | CHAR | 10 | 🔑 | BEA Register ID |
| 3 | `ITEM_NO` | NUMC | 3 | 🔑 | Item Number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `CCNUM` | CHAR | 25 |  | Payment Cards: Card Number |
| 6 | `EXPIRY_DATE` | CHAR | 7 |  | Credit Card Expiry Date |
| 7 | `KOINH` | CHAR | 60 |  | Account Holder Name |
| 8 | `CONTACT_PHONE` | CHAR | 12 |  | Contact Phone |
| 9 | `CONTACT_EMAIL` | CHAR | 255 |  | Contact Email |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 14 | `REG_DATE` | DATS | 8 |  | Register Date |
| 15 | `REG_BY` | CHAR | 12 |  | Register by |
| 16 | `DEL_IND` | CHAR | 1 |  | Deletion Indicator: Deleted? |
| 17 | `WITH_SIGNATURE` | CHAR | 1 |  | With Signature Indicator |

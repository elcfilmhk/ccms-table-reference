# ZISCRM_SERV_ORDER
**Description:** Outstanding service order details
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `zcl_isu_serv_ord_util`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `DEV_LOC` | CHAR | 30 |  | Device Location |
| 2 | `ORDER_NUM` | CHAR | 12 |  | Order Number |
| 3 | `PM_ACT_TYP` | CHAR | 3 |  | Maintenance activity type |
| 4 | `IPHAS` | CHAR | 1 |  | Maintenance Processing Phase |
| 5 | `ORDER_TYP` | CHAR | 4 |  | Order Type |
| 6 | `START_DATE` | DATS | 8 |  | Created on |
| 7 | `SO_DESC` | CHAR | 40 |  | Description |
| 8 | `STAT_PROFILE` | CHAR | 8 |  | Status Profile |
| 9 | `ROUTING_NO` | NUMC | 10 |  | Routing number of operations in the order |
| 10 | `ADR_NO` | CHAR | 10 |  | Address Number |
| 11 | `ENG_NAME` | CHAR | 20 |  | User field with 20 characters |
| 12 | `CONTACT_PERS` | CHAR | 40 |  | Name 1 |
| 13 | `CONTACT_PHONE` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 14 | `PM_ACT_DESC` | CHAR | 40 |  | Character field of length 40 |
| 15 | `STAT_WITH_NO` | CHAR | 40 |  | Character field of length 40 |
| 16 | `STAT_WO_NO` | CHAR | 40 |  | Character field of length 40 |
| 17 | `USER_RESPONSIBLE` | CHAR | 12 |  | Character Field of Length 12 |

# ZISCS_EEC_EP_ORDER
**Description:** FM Structure for an EcoPoint Order
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ziscseec_ep_trans__mpc`
- `ziscs0475_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | EcoPoints Order Header |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `ORDER_NO` | CHAR | 14 |  | EcoPoint Order Number |
| 4 | `ORDER_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `EP_TRANS_ID` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 7 | `ORD_COMPL_STATUS` | CHAR | 20 |  | EcoPoint Order Complete Status |
| 8 | `ORD_COMPL_BY` | CHAR | 12 |  | Order Complete User |
| 9 | `ORD_COMPL_DT` | CHAR | 14 |  | Order Complete Datetime [Format: YYYYMMDDhhmmss] |
| 10 | `ORDER_REMARKS` | CHAR | 255 |  | Text, 255 Characters |
| 11 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 12 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 14 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
| 15 | `DET_ITEM_LIST` | TTYP | 0 |  | Table of Order details |

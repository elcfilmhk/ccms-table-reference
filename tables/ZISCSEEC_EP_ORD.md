# ZISCSEEC_EP_ORD
**Description:** EcoPoints Order Header
**Total Fields:** 13
**Key Fields:** MANDT, ORDER_NO

## Programs Using This Table
- `ziscs0475_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORDER_NO` | CHAR | 14 | 🔑 | EcoPoint Order Number |
| 3 | `ORDER_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `EP_TRANS_ID` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 6 | `ORD_COMPL_STATUS` | CHAR | 20 |  | EcoPoint Order Complete Status |
| 7 | `ORD_COMPL_BY` | CHAR | 12 |  | Order Complete User |
| 8 | `ORD_COMPL_DT` | CHAR | 14 |  | Order Complete Datetime [Format: YYYYMMDDhhmmss] |
| 9 | `ORDER_REMARKS` | CHAR | 255 |  | Text, 255 Characters |
| 10 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 11 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 13 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

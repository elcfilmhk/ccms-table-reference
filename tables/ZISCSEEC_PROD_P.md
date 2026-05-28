# ZISCSEEC_PROD_P
**Description:** Product Price History
**Total Fields:** 11
**Key Fields:** MANDT, PROD_CODE, EFF_FM_DT

## Programs Using This Table
- `ziscs0472_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROD_CODE` | CHAR | 50 | 🔑 | EcoPoint Product Code |
| 3 | `EFF_FM_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `ORIG_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Original) |
| 6 | `ACTUAL_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Actual) |
| 7 | `DISP_PRIORITY` | INT4 | 10 |  | EP PRoduct Listing Priority(Descending) |
| 8 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 9 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 11 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

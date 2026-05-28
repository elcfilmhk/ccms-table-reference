# ZISCS_EEC_EP_PROD_LIST
**Description:** EcoPoints Product List
**Total Fields:** 25
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ziscseec_ep_trans__mpc`
- `ziscs0470_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Eco Point Product Master |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 4 | `PROD_NAME_EN` | CHAR | 500 |  | Product Name (EN) |
| 5 | `PROD_NAME_ZF` | CHAR | 500 |  | Product Name (ZF) |
| 6 | `PROD_DESC_EN` | CHAR | 500 |  | Description(EN) |
| 7 | `PROD_DESC_ZF` | CHAR | 300 |  | Description(ZF) |
| 8 | `MERC_CODE` | CHAR | 100 |  | Sponsor/Merchant Code |
| 9 | `INFINITE_STOCK` | CHAR | 1 |  | Infinite Stock Flag |
| 10 | `PROD_TERMS_URL_EN` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(EN) |
| 11 | `PROD_TERMS_URL_ZF` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(ZF) |
| 12 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 13 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 15 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
| 16 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 17 | `IMAGE_SAMPLE_URL_EN` | CHAR | 255 |  | Sample Image URL(EN) |
| 18 | `IMAGE_SAMPLE_URL_ZF` | CHAR | 255 |  | Sample Image URL(ZF) |
| 19 | `ORIG_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Original) |
| 20 | `ACTUAL_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Actual) |
| 21 | `DISP_PRIORITY` | INT4 | 10 |  | EP PRoduct Listing Priority(Descending) |
| 22 | `STOCK_BAL` | INT4 | 10 |  | Product Transaction Quantity (+: add Stock; -: reduced Stock |
| 23 | `MERC_NAME_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 24 | `MERC_NAME_ZF` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 25 | `TAG_LIST` | TTYP | 0 |  | Table of ZISCSEEC_TXTTAGS |

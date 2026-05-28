# ZISCS_EEC_EP_ORDER_DET
**Description:** FM Structure for an Order Detail Line
**Total Fields:** 36
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ziscseec_ep_trans__mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | EcoPoints Order Details |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `ORDER_NO` | CHAR | 14 |  | EcoPoint Order Number |
| 4 | `PROD_TRANS_ID` | CHAR | 32 |  | EcoPoints Product Transaction ID |
| 5 | `DISP_SEQ` | INT4 | 10 |  | Natural number |
| 6 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 7 | `ORDER_QTY` | INT4 | 10 |  | Order Product Quantity (+: Sold; -: Returned) |
| 8 | `ORIG_COST_EACH` | INT4 | 10 |  | Original EP Cost(+:Charge; -:Refund/Discnt) |
| 9 | `ORIG_COST_TTL` | INT4 | 10 |  | Original EP Cost(+:Charge; -:Refund/Discnt) |
| 10 | `ACTUAL_COST_TTL` | INT4 | 10 |  | Actual EP Cost of the Order (+:Charge; -:Refund/Discnt) |
| 11 | `PROD_OBJ` | STRU | 0 |  | EcoPoints Product List |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | Eco Point Product Master |
| 13 | `MANDT` | CLNT | 3 |  | Client |
| 14 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 15 | `PROD_NAME_EN` | CHAR | 500 |  | Product Name (EN) |
| 16 | `PROD_NAME_ZF` | CHAR | 500 |  | Product Name (ZF) |
| 17 | `PROD_DESC_EN` | CHAR | 500 |  | Description(EN) |
| 18 | `PROD_DESC_ZF` | CHAR | 300 |  | Description(ZF) |
| 19 | `MERC_CODE` | CHAR | 100 |  | Sponsor/Merchant Code |
| 20 | `INFINITE_STOCK` | CHAR | 1 |  | Infinite Stock Flag |
| 21 | `PROD_TERMS_URL_EN` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(EN) |
| 22 | `PROD_TERMS_URL_ZF` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(ZF) |
| 23 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 24 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 25 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 26 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
| 27 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 28 | `IMAGE_SAMPLE_URL_EN` | CHAR | 255 |  | Sample Image URL(EN) |
| 29 | `IMAGE_SAMPLE_URL_ZF` | CHAR | 255 |  | Sample Image URL(ZF) |
| 30 | `ORIG_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Original) |
| 31 | `ACTUAL_PRICE` | INT4 | 10 |  | EcoPoints Product Price (Actual) |
| 32 | `DISP_PRIORITY` | INT4 | 10 |  | EP PRoduct Listing Priority(Descending) |
| 33 | `STOCK_BAL` | INT4 | 10 |  | Product Transaction Quantity (+: add Stock; -: reduced Stock |
| 34 | `MERC_NAME_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 35 | `MERC_NAME_ZF` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 36 | `TAG_LIST` | TTYP | 0 |  | Table of ZISCSEEC_TXTTAGS |

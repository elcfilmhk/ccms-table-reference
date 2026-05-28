# ZISCS_EEC_EP_PROD_TRANS_INPUT
**Description:** In/Output structure for FM ZISCSEEC_EP_PROD_TX_CREATE
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0473_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EVAL_SEQ` | INT4 | 10 |  | Natural number |
| 2 | `.INCLUDE` | &nbsp; | 0 |  | EcoPoint Product transactions (Movement) |
| 3 | `MANDT` | CLNT | 3 |  | Client |
| 4 | `PROD_TRANS_ID` | CHAR | 32 |  | EcoPoints Product Transaction ID |
| 5 | `VALUE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 7 | `PROD_TRANS_REAS` | CHAR | 50 |  | Production Transaction Reason |
| 8 | `REF_NO` | CHAR | 80 |  | Char 80 |
| 9 | `PROD_TRANS_QTY` | INT4 | 10 |  | Product Transaction Quantity (+: add Stock; -: reduced Stock |
| 10 | `REMARKS` | CHAR | 255 |  | Text, 255 Characters |
| 11 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 12 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 14 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

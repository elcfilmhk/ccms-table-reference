# ZISCSEEC_EP_ORDD
**Description:** EcoPoints Order Details
**Total Fields:** 9
**Key Fields:** MANDT, ORDER_NO, PROD_TRANS_ID

## Programs Using This Table
- `ziscs0475_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORDER_NO` | CHAR | 14 | 🔑 | EcoPoint Order Number |
| 3 | `PROD_TRANS_ID` | CHAR | 32 | 🔑 | EcoPoints Product Transaction ID |
| 4 | `DISP_SEQ` | INT4 | 10 |  | Natural number |
| 5 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 6 | `ORDER_QTY` | INT4 | 10 |  | Order Product Quantity (+: Sold; -: Returned) |
| 7 | `ORIG_COST_EACH` | INT4 | 10 |  | Original EP Cost(+:Charge; -:Refund/Discnt) |
| 8 | `ORIG_COST_TTL` | INT4 | 10 |  | Original EP Cost(+:Charge; -:Refund/Discnt) |
| 9 | `ACTUAL_COST_TTL` | INT4 | 10 |  | Actual EP Cost of the Order (+:Charge; -:Refund/Discnt) |

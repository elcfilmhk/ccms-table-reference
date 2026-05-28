# ZISSDSOREFHDR
**Description:** Sales Order Reference for Retail Sales (Header)
**Total Fields:** 55
**Key Fields:** MANDT, SALES_ORDER_REF

## Programs Using This Table
- `zissd00085`
- `zissd00086`
- `zissd00086a`
- `zissd00096`
- `zissd00111`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_REF` | CHAR | 18 | 🔑 | Sales Order Reference Number |
| 3 | `STATUS` | CHAR | 2 |  | Status of Sales Order Reference |
| 4 | `BRANCH` | CHAR | 30 |  | Branch |
| 5 | `CA` | CHAR | 12 |  | Contract Account Number |
| 6 | `BP` | CHAR | 10 |  | Business Partner Number |
| 7 | `CONT_TITLE` | CHAR | 30 |  | Contact Person Title |
| 8 | `CONT_ENG_NAME` | CHAR | 80 |  | Contact Person Name (English) |
| 9 | `CONT_CHI_NAME` | CHAR | 80 |  | Contact Person Name (Chinese) |
| 10 | `CONT_TEL1` | CHAR | 30 |  | Contact Phone Number 1 |
| 11 | `CONT_TEL2` | CHAR | 30 |  | Contact Phone Number 2 |
| 12 | `CONT_TEL3` | CHAR | 30 |  | Contact Phone Number 3 |
| 13 | `EMAIL` | CHAR | 241 |  | E-Mail Address |
| 14 | `DEL_ADDR_ST3` | CHAR | 40 |  | Delivery Address - Street 3 |
| 15 | `DEL_ADDR_ST2` | CHAR | 40 |  | Delivery Address - Street 2 |
| 16 | `DEL_ADDR_HSE_NO` | CHAR | 10 |  | Delivery Address - House Number |
| 17 | `DEL_ADDR_ST` | CHAR | 60 |  | Delivery Address - Street |
| 18 | `DEL_ADDR_DIST` | CHAR | 40 |  | Delivery Address - District |
| 19 | `DEL_ADDR_REG` | CHAR | 3 |  | Delivery Address - Region |
| 20 | `DEL_ADDR_CHI` | CHAR | 120 |  | Delivery Address (Chinese) |
| 21 | `SHIP_TO` | CHAR | 10 |  | Ship-To Party |
| 22 | `SALES_ORDER` | CHAR | 10 |  | Sales Order Number |
| 23 | `SO_STATUS` | CHAR | 1 |  | Overall Status of Sales Order |
| 24 | `CURRENCY` | CUKY | 5 |  | Currency Key |
| 25 | `TOTAL_PRICE` | CURR | 15 |  | Total Price |
| 26 | `PRICING_DATE` | DATS | 8 |  | Pricing Date |
| 27 | `PYMT_TERM` | CHAR | 40 |  | Payment Terms |
| 28 | `PYMT_AMT` | CURR | 15 |  | Total Payment Amount |
| 29 | `PYMT_MEANS` | CHAR | 30 |  | Payment Means |
| 30 | `APPROVAL_CODE` | CHAR | 10 |  | Credit Card Approval Code |
| 31 | `PYMT_DATE` | DATS | 8 |  | Payment Date |
| 32 | `REF1` | CHAR | 10 |  | Reference 1 |
| 33 | `REF2` | CHAR | 10 |  | Reference 2 |
| 34 | `REF3` | CHAR | 10 |  | Reference 3 |
| 35 | `REF4` | CHAR | 10 |  | Reference 4 |
| 36 | `REF5` | CHAR | 10 |  | Reference 5 |
| 37 | `REF6` | CHAR | 10 |  | Reference 6 |
| 38 | `REF7` | CHAR | 10 |  | Reference 7 |
| 39 | `REF8` | CHAR | 10 |  | Reference 8 |
| 40 | `REF9` | CHAR | 10 |  | Reference 9 |
| 41 | `REF10` | CHAR | 10 |  | Reference 10 |
| 42 | `RMK_VENDOR` | CHAR | 100 |  | Remark to Vendor |
| 43 | `RMK_CUST` | CHAR | 100 |  | Remark to Customer |
| 44 | `PRINT_VERSION` | NUMC | 4 |  | Print Version |
| 45 | `REFERENCE` | CHAR | 130 |  | Reference |
| 46 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 47 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 48 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 49 | `UPDATE_DATE` | DATS | 8 |  | Last change date |
| 50 | `UPDATE_TIME` | TIMS | 6 |  | Last changed at |
| 51 | `UPDATED_BY` | CHAR | 12 |  | Last Changed by |
| 52 | `CANCEL_DATE` | DATS | 8 |  | Cancel date |
| 53 | `CANCEL_TIME` | TIMS | 6 |  | Cancel time |
| 54 | `CANCELLED_BY` | CHAR | 12 |  | Cancelled by |
| 55 | `PREV_CUST_REF` | CHAR | 18 |  | Previous Cust Ref No. |

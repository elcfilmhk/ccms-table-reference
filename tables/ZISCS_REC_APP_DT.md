# ZISCS_REC_APP_DT
**Description:** Re Cert Application
**Total Fields:** 46
**Key Fields:** MANDT, VKONT, ACKNO, ITEM_NO

## Programs Using This Table
- `ziscsrecappdata_write_documentft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ACKNO` | CHAR | 12 | 🔑 | Acknowledgement Number |
| 4 | `ITEM_NO` | NUMC | 3 | 🔑 | No. for Recurring Payment |
| 5 | `CUST_NAME` | CHAR | 60 |  | Contact Person Name |
| 6 | `ADD_NAME` | CHAR | 100 |  | Additional Name |
| 7 | `PROD_TYP` | CHAR | 2 |  | Re Source |
| 8 | `UNIT_PRICE` | CURR | 9 |  | Rate of Unit Purchased |
| 9 | `UNIT_PUR` | DEC | 11 |  | Total Unit Purchased |
| 10 | `PAY_METHOD` | CHAR | 3 |  | Payment Method |
| 11 | `PAID_AMNT` | CURR | 11 |  | Paid Amount |
| 12 | `CURRENCY` | CUKY | 5 |  | Transaction Currency |
| 13 | `PAYMENT_DATE` | DATS | 8 |  | Payment Date |
| 14 | `SUB_DATE` | DATS | 8 |  | Submission Date |
| 15 | `CCARD_ID` | CHAR | 6 |  | Payment Card ID |
| 16 | `CCNUM` | CHAR | 4 |  | Card Number |
| 17 | `CC_EXPIRY_DATE` | DATS | 8 |  | Credit Card Expiry Date |
| 18 | `ZTNUM` | CHAR | 13 |  | Cheque No |
| 19 | `CHEQUE_DAT` | DATS | 8 |  | Cheque Value Date |
| 20 | `PURCHASE_TYP` | CHAR | 10 |  | One-Off Multiple |
| 21 | `REC_NO_MONTH` | NUMC | 2 |  | No. of Months for recurring payment |
| 22 | `NOTICE_TO_CUST` | DATS | 8 |  | Date on which Notice Sent to Customer |
| 23 | `MATNR` | CHAR | 18 |  | Material Number |
| 24 | `VBELN` | CHAR | 10 |  | Sales Document |
| 25 | `POSNR` | NUMC | 6 |  | Sales Document Item |
| 26 | `RE_DED_YEAR` | CHAR | 4 |  | RE Deduction Year |
| 27 | `CON_PER_NAME` | CHAR | 60 |  | Contact Person Name |
| 28 | `CON_PHONE_NO` | CHAR | 10 |  | Contact Phone No. |
| 29 | `CON_METHOD` | CHAR | 2 |  | Contact Method |
| 30 | `CON_EMAIL` | CHAR | 40 |  | Contact Person Email |
| 31 | `PREF_TIME` | CHAR | 6 |  | Preferred time |
| 32 | `INCOMING_CHANNEL` | CHAR | 10 |  | Incoming Channel |
| 33 | `PUB_ENQ_ALLOW` | CHAR | 3 |  | Allow Publication |
| 34 | `REC_NO` | CHAR | 17 |  | RE Certificate No. |
| 35 | `REC_ISSUE_DAT` | DATS | 8 |  | RE Certificate Issue Date |
| 36 | `LANGUAGE` | CHAR | 2 |  | Language Code |
| 37 | `REC_APP_STATUS` | CHAR | 2 |  | RE Application Status |
| 38 | `CO2_VALUE` | DEC | 20 |  | CO2 reduction amount |
| 39 | `CO2_UNIT` | CHAR | 6 |  | CO2 Unit |
| 40 | `C_YEAR` | CHAR | 4 |  | Corresponding Year |
| 41 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 42 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 43 | `ERZET` | TIMS | 6 |  | Entry time |
| 44 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 45 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 46 | `AEZET` | TIMS | 6 |  | Time last change was made |

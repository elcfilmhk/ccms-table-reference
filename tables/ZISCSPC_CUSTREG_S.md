# ZISCSPC_CUSTREG_S
**Description:** Structure for Customer Registration BW
**Total Fields:** 24
**Key Fields:** _none_

## Programs Using This Table
- `z_bw_extract_cust_reg=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 2 | `REG_ID` | CHAR | 10 |  | Registration ID |
| 3 | `VALIDFROM` | DATS | 8 |  | Valid From Date |
| 4 | `VALIDTO` | DATS | 8 |  | Valid To Date |
| 5 | `CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 6 | `PROD_ID` | CHAR | 3 |  | Product ID |
| 7 | `SPECIAL_CODE` | CHAR | 20 |  | Special Code |
| 8 | `QRCODE` | CHAR | 50 |  | QR Code |
| 9 | `QRCODEVALID` | DATS | 8 |  | Valid To Date |
| 10 | `STATUS` | CHAR | 1 |  | Status for Merchant in PC |
| 11 | `BEN_ID` | CHAR | 2 |  | Beneficiary ID |
| 12 | `ES_CODE` | CHAR | 1 |  | Energy Saving Code |
| 13 | `DELETION_IND` | CHAR | 1 |  | Deletion Indicator |
| 14 | `WEL_GIFT` | CHAR | 2 |  | Welcome Gift |
| 15 | `SOURCE` | CHAR | 1 |  | Source |
| 16 | `SELF_INIT` | CHAR | 1 |  | Self-initiated |
| 17 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 18 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 19 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 20 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 21 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 22 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
| 23 | `GUID` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 24 | `REC_SOURCE` | CHAR | 1 |  | Recruitment Source |

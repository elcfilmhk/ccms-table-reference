# ZISCS_EEC_EP_TRN_HIST
**Description:** EcoPoint Transaction History Structure
**Total Fields:** 19
**Key Fields:** _none_

## Programs Using This Table
- `zcl_z_test_jlc6259_mpc`
- `zcl_ziscseec_ep_trans__mpc`
- `ziscs0386_eec`
- `ziscs0827`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Eco Points Transaction |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `EP_TRANS_ID` | CHAR | 32 |  | EcoPoints Transaction ID |
| 4 | `VALUE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `EP_TRANS_REASON` | CHAR | 50 |  | Eco Points Transaction Reason |
| 7 | `REF_NO` | CHAR | 80 |  | Char 80 |
| 8 | `EP_TRANS_AMT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 9 | `REMARKS` | CHAR | 255 |  | Remarks |
| 10 | `BAL_EXPIRY_FLAG` | CHAR | 1 |  | 'X': Special transaction to expire all remaining EP balance. |
| 11 | `LAST_BELNR` | CHAR | 12 |  | Number of a billing document |
| 12 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 13 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 15 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
| 16 | `BAL_CF` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 17 | `ORDER_OBJ` | TTYP | 0 |  | Table of ZISCS_EEC_EP_ORDER |
| 18 | `REASON_DESC_EN` | CHAR | 80 |  | Text (80 Characters) |
| 19 | `REASON_DESC_ZF` | CHAR | 80 |  | Text (80 Characters) |

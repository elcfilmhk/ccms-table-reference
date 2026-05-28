# ZISCS_EEC_CREATE_EP_TRN
**Description:** I/O Structure for FM
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0386_eec`
- `ziscs0474_eec`
- `ziscs0476_eec`
- `ziscseec_ep_conversion_create=ft`
- `ziscseec_ep_trans_create======ft`
- `ziscseec_ep_trans_reas_check==ft`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EVAL_SEQ` | INT4 | 10 |  | Natural number |
| 2 | `IGNORE_REASON_CHK` | CHAR | 1 |  | Single-Character Flag |
| 3 | `.INCLUDE` | &nbsp; | 0 |  | Eco Points Transaction |
| 4 | `MANDT` | CLNT | 3 |  | Client |
| 5 | `EP_TRANS_ID` | CHAR | 32 |  | EcoPoints Transaction ID |
| 6 | `VALUE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `EP_TRANS_REASON` | CHAR | 50 |  | Eco Points Transaction Reason |
| 9 | `REF_NO` | CHAR | 80 |  | Char 80 |
| 10 | `EP_TRANS_AMT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 11 | `REMARKS` | CHAR | 255 |  | Remarks |
| 12 | `BAL_EXPIRY_FLAG` | CHAR | 1 |  | 'X': Special transaction to expire all remaining EP balance. |
| 13 | `LAST_BELNR` | CHAR | 12 |  | Number of a billing document |
| 14 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 15 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 17 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

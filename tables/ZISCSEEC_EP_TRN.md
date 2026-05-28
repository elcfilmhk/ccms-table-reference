# ZISCSEEC_EP_TRN
**Description:** Eco Points Transaction
**Total Fields:** 14
**Key Fields:** MANDT, EP_TRANS_ID

## Programs Using This Table
- `z_ep_valid_tran`
- `zcl_ztest_ziscseec_ep__mpc`
- `ziscs0476_eec`
- `ziscs0494`
- `ziscs_migration_service_credit`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EP_TRANS_ID` | CHAR | 32 | 🔑 | EcoPoints Transaction ID |
| 3 | `VALUE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `EP_TRANS_REASON` | CHAR | 50 |  | Eco Points Transaction Reason |
| 6 | `REF_NO` | CHAR | 80 |  | Char 80 |
| 7 | `EP_TRANS_AMT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 8 | `REMARKS` | CHAR | 255 |  | Remarks |
| 9 | `BAL_EXPIRY_FLAG` | CHAR | 1 |  | 'X': Special transaction to expire all remaining EP balance. |
| 10 | `LAST_BELNR` | CHAR | 12 |  | Number of a billing document |
| 11 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 12 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 14 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

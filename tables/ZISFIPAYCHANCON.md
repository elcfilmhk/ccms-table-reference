# ZISFIPAYCHANCON
**Description:** Mobile Payment Configuration Table
**Total Fields:** 33
**Key Fields:** MANDT, OFFIC_EX, FROM_DATE

## Programs Using This Table
- `zisfi0282`
- `zisfi0310a`
- `zisfi0310b`
- `zisfi0311`
- `zisfi0311b`
- `zisfi0313`
- `zisfi0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 3 | `FROM_DATE` | DATS | 8 | 🔑 | Valid From Date |
| 4 | `TO_DATE` | DATS | 8 |  | Valid To Date |
| 5 | `ZZSUBTYP` | CHAR | 1 |  | Subscription Type |
| 6 | `SKALID` | CHAR | 2 |  | Factory Calendar |
| 7 | `ZZVARI` | CHAR | 4 |  | Value Date Variance |
| 8 | `ZZDBTVR` | CHAR | 4 |  | Debit Date Variance |
| 9 | `ZZPY_BA` | CHAR | 4 |  | Payment Posting - Business Area |
| 10 | `ZZCR_GL` | CHAR | 10 |  | Handling Charge - Credit GL Account |
| 11 | `ZZDR_GL` | CHAR | 10 |  | Handling Charge - Debit GL Account |
| 12 | `ZZCR_BA` | CHAR | 4 |  | Handling Charge - Credit Business Area |
| 13 | `ZZDR_BA` | CHAR | 4 |  | Handling Charge - Debit Business Area |
| 14 | `ZZKOSTL` | CHAR | 10 |  | Handling Charge - Cost Center |
| 15 | `ZZMETHOD` | CHAR | 10 |  | Interface Method |
| 16 | `ZZINPUT_DT` | CHAR | 10 |  | Input Date Selection for Close Payment Lot |
| 17 | `ZZSTART_TIM` | TIMS | 6 |  | Start Time |
| 18 | `ZZEND_TIM` | TIMS | 6 |  | End Time |
| 19 | `ZZREV_CNT_VAR` | CHAR | 4 |  | Reversal Count Variance |
| 20 | `ZZDOC_TYPE` | CHAR | 50 |  | Document Types |
| 21 | `ZZVALID` | CHAR | 255 |  | Additional Validations |
| 22 | `ZZCNT_VAL` | CHAR | 1 |  | Count Validation |
| 23 | `ZZAMT_VAL` | CHAR | 1 |  | Amount Validation |
| 24 | `ZZRECONVALID` | CHAR | 255 |  | Recon Mandatory field validations |
| 25 | `ZZRULETYPE` | CHAR | 2 |  | Unique ID Generation Rule Type |
| 26 | `ZZSFEERULETYPE` | CHAR | 2 |  | Service fee rule type |
| 27 | `ZZCALPAY_DT` | CHAR | 10 |  | Date for ZISFICALPAY date |
| 28 | `PYMTCHNL` | CHAR | 2 |  | Payment Channel |
| 29 | `ZBUDAT` | CHAR | 1 |  | Use Posting Date |
| 30 | `ZBLDAT` | CHAR | 1 |  | Use Document Date |
| 31 | `ZVALUT` | CHAR | 1 |  | Use Value Date |
| 32 | `ZBLOCK` | CHAR | 1 |  | Channel Blocked |
| 33 | `ZLIMIT` | CHAR | 4 |  | Payment Lot Limit |

# ZISCS_PYL_REG
**Description:** Power Your Love Registration
**Total Fields:** 27
**Key Fields:** MANDT, PYL_ID, CTR_ACC_ID

## Programs Using This Table
- `ziscs0369_pyl`
- `ziscs0370_pyl`
- `ziscs0401`
- `ziscs0403`
- `ziscs0404`
- `zisfi0253`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EMAIL` | CHAR | 100 |  | Email |
| 5 | `CONTACT` | CHAR | 20 |  | Contact Number |
| 6 | `SP_CODE` | CHAR | 20 |  | Speical Code |
| 7 | `TOTAL_AMT` | CURR | 13 |  | Total Amount |
| 8 | `PAID_AMT` | CURR | 13 |  | Paid Amount |
| 9 | `ENG_SAV` | CHAR | 1 |  | Energy Saving Indicator (Y/N) |
| 10 | `HARD_COPY` | CHAR | 1 |  | Hard Copy Indicator (Y/N) |
| 11 | `DISPLAY_NAME` | CHAR | 55 |  | Display Name |
| 12 | `PNOTE` | CHAR | 12 |  | Payment Note no |
| 13 | `REFERRER` | CHAR | 12 |  | Referrer |
| 14 | `SOURCE` | CHAR | 1 |  | Source |
| 15 | `STATUS` | CHAR | 1 |  | Status |
| 16 | `SELF_INIT_IND` | CHAR | 1 |  | Self initiate indiciator |
| 17 | `REPEAT_IND` | CHAR | 1 |  | Repeat Customer Indicator |
| 18 | `LANGUAGE` | LANG | 1 |  | Language Key |
| 19 | `EVENT_GIFT_IND` | CHAR | 1 |  | Event Registration Gift Indicator |
| 20 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 21 | `ERZET` | TIMS | 6 |  | Entry time |
| 22 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 23 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 24 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 25 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 26 | `MERCHANT_ID` | CHAR | 3 |  | Merchant ID |
| 27 | `BATCH_ID` | CHAR | 3 |  | ECoupon ID |

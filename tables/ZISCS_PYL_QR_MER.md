# ZISCS_PYL_QR_MER
**Description:** Power Your Love Merchant Master
**Total Fields:** 16
**Key Fields:** MANDT, PYL_ID, MERCHANT_ID, BATCH_ID

## Programs Using This Table
- `ziscs0367_pyl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `MERCHANT_ID` | CHAR | 3 | 🔑 | Merchant ID |
| 4 | `BATCH_ID` | CHAR | 3 | 🔑 | ECoupon ID |
| 5 | `ECOUPON_NAME` | CHAR | 80 |  | ECoupon Name |
| 6 | `VALID_FROM_DATE` | DATS | 8 |  | QR code valid from |
| 7 | `VALID_TO_DATE` | DATS | 8 |  | QR code valid to |
| 8 | `MERCHANT_NAME` | CHAR | 80 |  | Merchant Name |
| 9 | `CAMPAIGN_ID` | CHAR | 24 |  | CRM Campaign |
| 10 | `ACTIVE` | CHAR | 1 |  | Active |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERZET` | TIMS | 6 |  | Entry time |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 16 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

# ZISCS_PYL_QR_MAP
**Description:** Power Your Love QR Code mapping
**Total Fields:** 14
**Key Fields:** MANDT, PYL_ID, MERCHANT_ID, BATCH_ID, QR_CODE_MAPPING

## Programs Using This Table
- `ziscs0367_pyl`
- `ziscs0401`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `MERCHANT_ID` | CHAR | 3 | 🔑 | Merchant ID |
| 4 | `BATCH_ID` | CHAR | 3 | 🔑 | ECoupon ID |
| 5 | `QR_CODE_MAPPING` | CHAR | 30 | 🔑 | QR Code Mapping |
| 6 | `CODE_TYPE` | CHAR | 1 |  | Code Type |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `QR_CODE_ENC` | CHAR | 100 |  | Encrypted QR Code |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERZET` | TIMS | 6 |  | Entry time |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 14 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

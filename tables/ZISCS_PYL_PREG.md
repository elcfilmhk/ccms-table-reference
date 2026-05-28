# ZISCS_PYL_PREG
**Description:** Power Your Love Pregistration Table
**Total Fields:** 16
**Key Fields:** MANDT, PYL_ID, EMAIL, CONTACT

## Programs Using This Table
- `z_bapi_emkt_async_remind_emailft`
- `ziscs0369_pyl`
- `ziscs0402`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `EMAIL` | CHAR | 100 | 🔑 | Email |
| 4 | `CONTACT` | CHAR | 20 | 🔑 | Contact Number |
| 5 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 6 | `VALID_TO_DT` | DATS | 8 |  | Valid To Date |
| 7 | `VALID_TO_TIME` | TIMS | 6 |  | Valid To Time |
| 8 | `COUNTER` | INT2 | 5 |  | 2 byte integer (signed) |
| 9 | `LAST_SEND_DATE` | DATS | 8 |  | Power Your Love Date |
| 10 | `LAST_SEND_TIME` | TIMS | 6 |  | Power Your Love Time |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERZET` | TIMS | 6 |  | Entry time |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `BATCH_ID` | CHAR | 3 |  | ECoupon ID |
| 15 | `MERCHANT_ID` | CHAR | 3 |  | Merchant ID |
| 16 | `SOURCE` | CHAR | 1 |  | PYL Source Channel |

# ZISBIPLOVEREF
**Description:** Power Your Love Correspondence Outbox & History for Referral
**Total Fields:** 15
**Key Fields:** MANDT, REF_CORR_ID

## Programs Using This Table
- `zisbi0188`
- `zisbi0199`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REF_CORR_ID` | NUMC | 10 | 🔑 | Unique ID of "Power Your Love" Referral correspondences |
| 3 | `CTR_ACC_ID` | CHAR | 12 |  | Contract Account Number |
| 4 | `TOKEN` | CHAR | 128 |  | Activitation Token |
| 5 | `EBILL_SENDER` | CHAR | 100 |  | Email sender address name |
| 6 | `REFER_EMAIL` | CHAR | 100 |  | Refer Email |
| 7 | `DISPLAY_NAME` | CHAR | 55 |  | Display Name |
| 8 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 9 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERZET` | TIMS | 6 |  | Entry time |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

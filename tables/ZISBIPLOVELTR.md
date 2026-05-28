# ZISBIPLOVELTR
**Description:** Power Your Love Correspondence Outbox & History for CA
**Total Fields:** 19
**Key Fields:** MANDT, CA_CORR_ID

## Programs Using This Table
- `zisbi0187`
- `zisbi0188`
- `zisbi0199`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CA_CORR_ID` | NUMC | 10 | 🔑 | Unique ID of "Power Your Love" CA correspondences |
| 3 | `CTR_ACC_ID` | CHAR | 12 |  | Contract Account Number |
| 4 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 5 | `EBILL_SENDER` | CHAR | 100 |  | Email sender address name |
| 6 | `EMAIL` | CHAR | 100 |  | Email |
| 7 | `TOTAL_AMT` | DEC | 13 |  | Power Your Love Payment Note Amount |
| 8 | `ENG_SAV` | CHAR | 1 |  | Energy Saving Indicator (Y/N) |
| 9 | `PNOTE` | CHAR | 12 |  | Payment Note no |
| 10 | `WELCOME` | CHAR | 1 |  | 'X': Need to send welcome message; others: no need |
| 11 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 12 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 13 | `BATCH_RUN_DATE` | DATS | 8 |  | Batch Run Date |
| 14 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 15 | `ERZET` | TIMS | 6 |  | Entry time |
| 16 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 17 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 18 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 19 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

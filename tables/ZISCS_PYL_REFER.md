# ZISCS_PYL_REFER
**Description:** Power Your Love Referral
**Total Fields:** 13
**Key Fields:** MANDT, CTR_ACC_ID, REFER_EMAIL

## Programs Using This Table
- `ziscs0370_pyl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REFER_EMAIL` | CHAR | 100 | 🔑 | Refer Email |
| 4 | `DISPLAY_NAME` | CHAR | 55 |  | Display Name |
| 5 | `REFER_CA` | CHAR | 12 |  | Refer CA |
| 6 | `STATUS` | CHAR | 1 |  | Status |
| 7 | `TOKEN` | CHAR | 128 |  | Activitation Token |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

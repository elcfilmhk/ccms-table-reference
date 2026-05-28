# ZISCSCCAUTOPAY
**Description:** Online Credit Card Autopay  cancelled Application
**Total Fields:** 12
**Key Fields:** MANDT, BUSINESSPARTNER, CONTRACTACCOUNT, ERDAT, ERZET

## Programs Using This Table
- `zisfi0278`
- `ztest_sapmzcs380`
- `ztest_zisfi0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUSINESSPARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `CONTRACTACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `STATUS` | CHAR | 1 |  | Credit Card Autopay Application Status |
| 11 | `CELLING` | CHAR | 1 |  | Incoming Payment Method |
| 12 | `CCARD_ID` | CHAR | 6 |  | Payment Card ID for Incoming Payments |

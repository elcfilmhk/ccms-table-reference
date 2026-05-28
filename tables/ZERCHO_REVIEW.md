# ZERCHO_REVIEW
**Description:** Billing Document release/reversal review table
**Total Fields:** 9
**Key Fields:** MANDT, BELNR, VALIDATION

## Programs Using This Table
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `VALIDATION` | CHAR | 10 | 🔑 | Name of billing validation |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 6 | `REVIEW` | CHAR | 1 |  | Send for Review |
| 7 | `USERID_LEVEL1` | CHAR | 12 |  | 1st Level user ID |
| 8 | `USERID_LEVEL2` | CHAR | 12 |  | 2nd Level User Id |
| 9 | `RDATE` | DATS | 8 |  | Date of Review |

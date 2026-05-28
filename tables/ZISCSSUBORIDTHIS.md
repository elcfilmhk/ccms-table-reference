# ZISCSSUBORIDTHIS
**Description:** CEP: Mapping Table of substituted data and original data
**Total Fields:** 15
**Key Fields:** MANDT, SOURCEFROM, ORIGINAL_CA, CREATE_DATE, CREATE_TIME

## Programs Using This Table
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `ORIGINAL_CA` | CHAR | 12 | 🔑 | Original Contract Account |
| 4 | `CREATE_DATE` | DATS | 8 | 🔑 | Date |
| 5 | `CREATE_TIME` | TIMS | 6 | 🔑 | Time |
| 6 | `SUBSTITUTED_KEY` | CHAR | 40 |  | Key from source |
| 7 | `ORIGINAL_BP` | CHAR | 10 |  | Original business partner |
| 8 | `ORIGINAL_PREMISE` | CHAR | 10 |  | Original Premise |
| 9 | `ORIGINAL_EMAIL` | CHAR | 255 |  | Original Email |
| 10 | `ORIGINAL_SP_ID` | CHAR | 10 |  | Original Service Point ID |
| 11 | `SUBST_BP` | CHAR | 100 |  | Substituted Value |
| 12 | `SUBST_CA` | CHAR | 100 |  | Substituted Value |
| 13 | `SUBST_PREMISE` | CHAR | 100 |  | Substituted Value |
| 14 | `SUBST_EMAIL` | CHAR | 100 |  | Substituted Value |
| 15 | `SUBST_SP_ID` | CHAR | 100 |  | Substituted Value |

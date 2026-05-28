# ZISCSSUBORIDATA
**Description:** CEP: Mapping Table of substituted data and original data
**Total Fields:** 13
**Key Fields:** MANDT, SOURCEFROM, ORIGINAL_CA

## Programs Using This Table
- `zisbi0167_bw`
- `ziscs0354`
- `ziscs0444`
- `ziscs0445`
- `ziscs0449`
- `ziscs0452`
- `ziscs0456`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `ORIGINAL_CA` | CHAR | 12 | 🔑 | Original Contract Account |
| 4 | `SUBSTITUTED_KEY` | CHAR | 40 |  | Key from source |
| 5 | `ORIGINAL_BP` | CHAR | 10 |  | Original business partner |
| 6 | `ORIGINAL_PREMISE` | CHAR | 10 |  | Original Premise |
| 7 | `ORIGINAL_EMAIL` | CHAR | 255 |  | Original Email |
| 8 | `ORIGINAL_SP_ID` | CHAR | 10 |  | Original Service Point ID |
| 9 | `SUBST_BP` | CHAR | 100 |  | Substituted Value |
| 10 | `SUBST_CA` | CHAR | 100 |  | Substituted Value |
| 11 | `SUBST_PREMISE` | CHAR | 100 |  | Substituted Value |
| 12 | `SUBST_EMAIL` | CHAR | 100 |  | Substituted Value |
| 13 | `SUBST_SP_ID` | CHAR | 100 |  | Substituted Value |

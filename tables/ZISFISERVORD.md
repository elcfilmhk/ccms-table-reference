# ZISFISERVORD
**Description:** Service order for Dunning DC & RC
**Total Fields:** 9
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `zisfi0242_d`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `AUART` | CHAR | 4 |  | Order Type |
| 4 | `ADDAT` | DATS | 8 |  | PM Order: Reference Date |
| 5 | `LAST_IPHAS` | CHAR | 1 |  | Maintenance Processing Phase |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `PARNR` | CHAR | 12 |  | Partner |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |

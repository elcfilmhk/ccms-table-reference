# ZISBISIMDOC
**Description:** Simulation doc. for left out calculation
**Total Fields:** 8
**Key Fields:** MANDT, PERIOD, VERTRAG

## Programs Using This Table
- `zisbi0015`
- `zisbi0015_1`
- `ziscs0084`
- `zisfi0043`
- `zisfi0083`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0083_2`
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `BWUPD` | CHAR | 1 |  | Flag for BW updated |
| 8 | `POST_DATE` | DATS | 8 |  | System Date |

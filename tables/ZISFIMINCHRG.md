# ZISFIMINCHRG
**Description:** Minimun charge of left out outline contract
**Total Fields:** 9
**Key Fields:** MANDAT, PERIOD, VERTRAG

## Programs Using This Table
- `zisbi0015`
- `zisbi0015_1`
- `ziscs0084`
- `zisfi0083`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0083_2`
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDAT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `WERT1` | DEC | 16 |  | Entry value (installed value) for a device |
| 5 | `MIN_CHARGE` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 6 | `BATCH_RUN_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `BWUPD` | CHAR | 1 |  | Flag for BW updated |
| 9 | `POST_DATE` | DATS | 8 |  | System Date |

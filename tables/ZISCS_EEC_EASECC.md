# ZISCS_EEC_EASECC
**Description:** EA Application Secondary Contract Accounts
**Total Fields:** 5
**Key Fields:** MANDT, EA_APP_NO, SEC_VKONT

## Programs Using This Table
- `ziscs0723`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EA_APP_NO` | CHAR | 12 | 🔑 | Energy Audit Application |
| 3 | `SEC_VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

# ZISFIDUNNING
**Description:** Events: Dunning Procedure
**Total Fields:** 5
**Key Fields:** MANDT, MAHNV

## Programs Using This Table
- `zisfi0189`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAHNV` | CHAR | 2 | 🔑 | Dunning Procedure |
| 3 | `EVT1211_DAYS` | NUMC | 3 |  | Dunning frequency in days |
| 4 | `EVT0300_DISC` | NUMC | 3 |  | Days of selecting disconnection document |
| 5 | `EVT0300_DEP` | DEC | 8 |  | Overdue amt over X times security deposit |

# ZISDMMRUTAR
**Description:** Mapping between rate category and MRU allocation
**Total Fields:** 6
**Key Fields:** MANDT, CHECK_PARAM, SYSTARIFF, TARIFTYP

## Programs Using This Table
- `zisdm0015`
- `zisdm0105`
- `zisdm0106`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHECK_PARAM` | CHAR | 1 | 🔑 | Check field (Yes/ No) |
| 3 | `SYSTARIFF` | CHAR | 1 | 🔑 | System Tariff Indicatior |
| 4 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

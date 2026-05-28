# ZISMDOLDMDMSMTR
**Description:** Migrated MDMS 5.3 meter
**Total Fields:** 5
**Key Fields:** MANDT, SERNR

## Programs Using This Table
- `zised0012`
- `zised0057`
- `zismd0039`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `ERTIM` | TIMS | 6 |  | Time, at Which Record Was Added |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

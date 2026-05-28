# ZJIVS_TABL
**Description:** Tables to be exported
**Total Fields:** 7
**Key Fields:** MANDT, MIGOBJ, TABNAME

## Programs Using This Table
- `zjivs_export_job`
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `POSNR` | NUMC | 6 |  | Sort field |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZEI` | TIMS | 6 |  | Time when record was added |

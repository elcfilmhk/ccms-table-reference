# ZISMDLASTPFDATE
**Description:** Last load profile migration date
**Total Fields:** 7
**Key Fields:** MANDT, ANLAGE, SERNR, ZWNUMMER

## Programs Using This Table
- `zismd0012`
- `zismd0019`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 6 | `LAST_PROF_DATE` | DATS | 8 |  | Field of type DATS |
| 7 | `LAST_PROF_TIME` | TIMS | 6 |  | Field of type TIMS |

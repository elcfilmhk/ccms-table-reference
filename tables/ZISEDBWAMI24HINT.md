# ZISEDBWAMI24HINT
**Description:** EDM - Export table
**Total Fields:** 15
**Key Fields:** MANDT, JOBNAME, REC

## Programs Using This Table
- `zised0054`
- `zised0055`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `REC` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 5 | `PROFVALDAY` | DATS | 8 |  | Profile date, normally Snapshot date - 1 |
| 6 | `SERNR` | CHAR | 18 |  | Serial Number |
| 7 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 8 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 9 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 10 | `ANLAGE` | CHAR | 10 |  | Installation |
| 11 | `MASSBILL` | UNIT | 3 |  | Unit of measurement for meter reading |
| 12 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 13 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 14 | `LENGTH` | INT2 | 5 |  | Output data length |
| 15 | `DATA` | LCHR | 32000 |  | Output data in Export format |

# ZISEDEXP
**Description:** EDM - Export table
**Total Fields:** 8
**Key Fields:** MANDT, JOBNAME, REC

## Programs Using This Table
- `zised0016`
- `zised0018`
- `zised0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `REC` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `DATUM` | DATS | 8 |  | Date |
| 6 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 7 | `LENGTH` | INT2 | 5 |  | Output data length |
| 8 | `DATA` | LCHR | 32000 |  | Output data in Export format |

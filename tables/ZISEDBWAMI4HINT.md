# ZISEDBWAMI4HINT
**Description:** Export table for daily extraction of AMI profile value to BW
**Total Fields:** 11
**Key Fields:** MANDT, SNAPSHOT_DATE, SNAPSHOT_TIME, PROFILE, SERNR, ZWNUMMER

## Programs Using This Table
- `zised0052`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SNAPSHOT_DATE` | DATS | 8 | 🔑 | Date (Snapshot) |
| 3 | `SNAPSHOT_TIME` | TIMS | 6 | 🔑 | Time (Snapshot) |
| 4 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 9 | `PROFVALDAY` | DATS | 8 |  | Profile date, normally Snapshot date - 1 |
| 10 | `PROFVALFLAG` | CHAR | 1 |  | Profile Available Flag |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |

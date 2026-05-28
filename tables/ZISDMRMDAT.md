# ZISDMRMDAT
**Description:** Route Management Statistics Intermediate Table
**Total Fields:** 17
**Key Fields:** MANDT, DATATYPE, MAINMRU, MRU, CONNOBJ, MRMETHOD, JOBNO

## Programs Using This Table
- `zisdm0026`
- `zisdm0085`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATATYPE` | CHAR | 1 | 🔑 | Route Management Data Type |
| 3 | `MAINMRU` | CHAR | 8 | 🔑 | Main Meter Reading Unit |
| 4 | `MRU` | CHAR | 8 | 🔑 | Meter reading unit |
| 5 | `CONNOBJ` | CHAR | 30 | 🔑 | Connection Object |
| 6 | `MRMETHOD` | CHAR | 8 | 🔑 | Meter Reading Method |
| 7 | `JOBNO` | NUMC | 5 | 🔑 | Process ID |
| 8 | `NEXTMRDATE` | DATS | 8 |  | Scheduled meter reading date |
| 9 | `ADDRESS1` | CHAR | 50 |  | Address Text Line |
| 10 | `ADDRESS2` | CHAR | 50 |  | Address Text Line |
| 11 | `ADDRESS3` | CHAR | 50 |  | Address Text Line |
| 12 | `ADDRESS4` | CHAR | 50 |  | Address Text Line |
| 13 | `GSTCNT` | CHAR | 8 |  | Record Count |
| 14 | `DTCNT` | CHAR | 8 |  | Record Count |
| 15 | `BTCNT` | CHAR | 8 |  | Record Count |
| 16 | `LPTCNT` | CHAR | 8 |  | Record Count |
| 17 | `OTHCNT` | CHAR | 8 |  | Record Count |

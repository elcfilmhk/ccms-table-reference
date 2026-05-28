# ZJIVS_SETDATA_SINGLE
**Description:** 
**Total Fields:** 12
**Key Fields:** MANDT, ZZJIVS_LINE_NUMBER, ZZJIVS_TABLE, ZZJIVS_SETNR

## Programs Using This Table
- `zjivs_export_setdata`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZJIVS_LINE_NUMBER` | NUMC | 15 | 🔑 | JiVS Line Number |
| 3 | `ZZJIVS_TABLE` | CHAR | 30 | 🔑 | Table for set |
| 4 | `ZZJIVS_SETNR` | CHAR | 12 | 🔑 | Set ID (internal) |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Data for a Set Line (S Set) |
| 6 | `CLASS` | CHAR | 4 |  | Set class |
| 7 | `SETNR` | CHAR | 34 |  | Identification of a set |
| 8 | `PRTCLASS` | CHAR | 1 |  | Format group |
| 9 | `LNAME` | CHAR | 8 |  | Symbolic name (Report Writer) |
| 10 | `FLAG` | CHAR | 1 |  | Ind.: Suppress interval/hierarchy (Report Writer) |
| 11 | `PMFLAG` | CHAR | 1 |  | +/- sign indicator (Report Writer) |
| 12 | `OLD_LINE` | NUMC | 10 |  | Set line counter |

# ZJIVS_SETDATA_MULTI
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
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Data for a Set Line (M Set) |
| 6 | `CLASS` | CHAR | 4 |  | Set class |
| 7 | `SETNR` | CHAR | 34 |  | Identification of a set |
| 8 | `FLAG` | CHAR | 1 |  | Ind.: Suppress interval/hierarchy (Report Writer) |
| 9 | `PRTCLASS` | CHAR | 1 |  | Format group |
| 10 | `LNAME` | CHAR | 8 |  | Symbolic name (Report Writer) |
| 11 | `LFIELDNAME` | CHAR | 30 |  | Field Name |
| 12 | `OLD_LINE` | NUMC | 10 |  | Set line counter |

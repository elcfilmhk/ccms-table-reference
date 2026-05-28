# ZJIVS_SETDATA_HEADER
**Description:** 
**Total Fields:** 21
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
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Data Description of a Set (Without Values) |
| 6 | `CLASS` | CHAR | 4 |  | Set class |
| 7 | `TABLE` | CHAR | 30 |  | Table for set |
| 8 | `SETNR` | CHAR | 34 |  | Identification of a set |
| 9 | `TYPE` | CHAR | 1 |  | Set type |
| 10 | `XDYNAMIC` | CHAR | 1 |  | Flag: Dynamic set |
| 11 | `TITLE` | CHAR | 40 |  | Short description of a set |
| 12 | `FIELD` | CHAR | 30 |  | Field name |
| 13 | `RVALUE` | CHAR | 24 |  | Representative value of a set |
| 14 | `SNAME` | CHAR | 8 |  | Symbolic name (Report Writer) |
| 15 | `UNIQUE` | CHAR | 1 |  | X flag: Must be unique |
| 16 | `AUTHGR` | CHAR | 4 |  | Authorization group |
| 17 | `SEARCHFLD` | CHAR | 10 |  | Search help field for set |
| 18 | `PRTCLASS` | CHAR | 1 |  | Format group (set header) |
| 19 | `CREUSER` | CHAR | 12 |  | Created By |
| 20 | `UPDUSER` | CHAR | 12 |  | Last Changed By |
| 21 | `SET_OLANGU` | LANG | 1 |  | Original Language for Sets (SAP Internal Only) |

# ZFILE_COMP_RSLT
**Description:** File Comparison Result
**Total Fields:** 14
**Key Fields:** MANDT, DATUM, UZEIT, UNAME, RESULT_LINE

## Programs Using This Table
- `zfile_compare`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | Time |
| 4 | `UNAME` | CHAR | 12 | 🔑 | User Name |
| 5 | `RESULT_LINE` | NUMC | 5 | 🔑 | Result Line |
| 6 | `FOLDER1` | CHAR | 200 |  | Folder 1 |
| 7 | `FILE1` | CHAR | 200 |  | File 1 |
| 8 | `FOLDER2` | CHAR | 200 |  | Folder 2 |
| 9 | `FILE2` | CHAR | 200 |  | File 2 |
| 10 | `RESULT_ICON` | CHAR | 4 |  | Icon in text fields (substitute display, alias) |
| 11 | `LINE_NUMBER` | INT4 | 10 |  | Line Number |
| 12 | `DIFF_AT` | NUMC | 5 |  | Different at |
| 13 | `CONTENT1` | CHAR | 1000 |  | File Line Content |
| 14 | `CONTENT2` | CHAR | 1000 |  | File Line Content 2 |

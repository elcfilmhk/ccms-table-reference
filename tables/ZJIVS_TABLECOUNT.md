# ZJIVS_TABLECOUNT
**Description:** JiVS-Package: Log Creation of Number Table Entries
**Total Fields:** 11
**Key Fields:** MANDT, PROJECT, TABNAME

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROJECT` | CHAR | 30 | 🔑 | Project in ZJIVS_TABLECOUNT |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `TABCLASS` | CHAR | 8 |  | Table category |
| 5 | `COUNT_REC` | DEC | 15 |  | Number of exported data records |
| 6 | `CREAT_DATE` | DATS | 8 |  | Date of export run |
| 7 | `CREAT_TIME` | TIMS | 6 |  | Time of export run |
| 8 | `RUNSTAT` | CHAR | 10 |  | JiVS-Package: State of export of one table in LOG file |
| 9 | `END_DATE` | DATS | 8 |  | Date of export run |
| 10 | `END_TIME` | TIMS | 6 |  | Time of export run |
| 11 | `RUNTIME_MS` | DEC | 15 |  | Run time of export in milliseconds |

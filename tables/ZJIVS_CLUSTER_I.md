# ZJIVS_CLUSTER_I
**Description:** Informations about table cluster
**Total Fields:** 8
**Key Fields:** MANDT, PROJECT, SQLTAB, TABNAME

## Programs Using This Table
- `zjivs_create_table_count`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROJECT` | CHAR | 30 | 🔑 | Project in ZJIVS_TABLECOUNT |
| 3 | `SQLTAB` | CHAR | 10 | 🔑 | SQL table name |
| 4 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 5 | `ZZCLUSTER` | DEC | 16 |  | Count |
| 6 | `ZZTABLE` | DEC | 16 |  | Count |
| 7 | `CRDATE` | DATS | 8 |  | Created On |
| 8 | `CRTIME` | TIMS | 6 |  | Calendar: Created or Changed At |

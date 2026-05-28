# ZISBIINSERT
**Description:** The insert for a bill
**Total Fields:** 19
**Key Fields:** MANDT, INSERT_NO

## Programs Using This Table
- `zis_batch_insert_message======ft`
- `zis_new_batch_criteria========ft`
- `zisbi0005`
- `zisbi0010`
- `zisbi0150`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INSERT_NO` | NUMC | 10 | 🔑 | Insert Number |
| 3 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 4 | `BATCH_NO` | NUMC | 10 |  | Batch Number |
| 5 | `VALID_FROM` | DATS | 8 |  | Valid From Date |
| 6 | `VALID_TO` | DATS | 8 |  | Valid To Date |
| 7 | `PRIORITY` | NUMC | 6 |  | Priority |
| 8 | `INS_DESC1` | CHAR | 50 |  | The bill insert description |
| 9 | `EN_FILENAME1` | CHAR | 40 |  | The name of the file in english |
| 10 | `CH_FILENAME1` | CHAR | 40 |  | The name of the file in chinese |
| 11 | `INS_DESC2` | CHAR | 50 |  | The bill insert description |
| 12 | `EN_FILENAME2` | CHAR | 40 |  | The name of the file in english |
| 13 | `CH_FILENAME2` | CHAR | 40 |  | The name of the file in chinese |
| 14 | `INS_DESC3` | CHAR | 50 |  | The bill insert description |
| 15 | `EN_FILENAME3` | CHAR | 40 |  | The name of the file in english |
| 16 | `CH_FILENAME3` | CHAR | 40 |  | The name of the file in chinese |
| 17 | `INS_DESC4` | CHAR | 50 |  | The bill insert description |
| 18 | `EN_FILENAME4` | CHAR | 40 |  | The name of the file in english |
| 19 | `CH_FILENAME4` | CHAR | 40 |  | The name of the file in chinese |

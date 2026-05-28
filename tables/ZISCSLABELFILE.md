# ZISCSLABELFILE
**Description:** Insert Entries to Label Printing File
**Total Fields:** 5
**Key Fields:** MANDT, REQ_DATE, REQ_NO, FILE_NO

## Programs Using This Table
- `ziscs0138`
- `ziscs0141`
- `ziscs0143`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DATE` | DATS | 8 | 🔑 | Label request date |
| 3 | `REQ_NO` | CHAR | 4 | 🔑 | Request number |
| 4 | `FILE_NO` | NUMC | 2 | 🔑 | File Number |
| 5 | `FILE_PATH` | CHAR | 80 |  | File  Path |

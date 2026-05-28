# ZFILE_COMP_CONF
**Description:** File Comparison Configuration
**Total Fields:** 8
**Key Fields:** MANDT, INTERFACE, LINE_TYPE, LINE_NUMBER, CPOSITION

## Programs Using This Table
- `zfile_compare`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INTERFACE` | CHAR | 20 | 🔑 | File Interface |
| 3 | `LINE_TYPE` | CHAR | 1 | 🔑 | Line Type |
| 4 | `LINE_NUMBER` | INT4 | 10 | 🔑 | Line Number |
| 5 | `CPOSITION` | NUMC | 4 | 🔑 | Character Position in a Line |
| 6 | `LENGTH` | NUMC | 4 |  | No. of Characters |
| 7 | `SKIP` | CHAR | 1 |  | Skip Checking? |
| 8 | `REMARKS` | CHAR | 50 |  | Text Field |

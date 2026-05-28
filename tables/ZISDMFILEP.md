# ZISDMFILEP
**Description:** Physical path file for import and export
**Total Fields:** 4
**Key Fields:** MANDT, UNAME, TYPE

## Programs Using This Table
- `zisdm0009`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNAME` | CHAR | 12 | 🔑 | User Name |
| 3 | `TYPE` | CHAR | 6 | 🔑 | Import & Export type |
| 4 | `PATH` | CHAR | 60 |  | File name |

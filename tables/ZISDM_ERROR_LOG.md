# ZISDM_ERROR_LOG
**Description:** Table to store errors while creating/Modifying service order
**Total Fields:** 9
**Key Fields:** MANDT, GUID, MSG_NO, MSG_ID

## Programs Using This Table
- `zisdm_so_approval`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GUID` | RAW | 16 | 🔑 | Globally Unique Identifier |
| 3 | `MSG_NO` | NUMC | 3 | 🔑 | Message Number |
| 4 | `MSG_ID` | CHAR | 20 | 🔑 | Message Class |
| 5 | `MSG_VAR1` | CHAR | 50 |  | Message Variable |
| 6 | `MSG_VAR2` | CHAR | 50 |  | Message Variable |
| 7 | `MSG_VAR3` | CHAR | 50 |  | Message Variable |
| 8 | `MSG_VAR4` | CHAR | 50 |  | Message Variable |
| 9 | `CREATED_ON` | DATS | 8 |  | Created On |

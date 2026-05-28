# ZISCSEEC_OBJTOKN
**Description:** Stores Tokens for EE&C
**Total Fields:** 11
**Key Fields:** MANDT, TOKEN

## Programs Using This Table
- `ziscs0397_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TOKEN` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 3 | `TOKEN_TY` | CHAR | 20 |  | Token Types |
| 4 | `OBJECT_STRING` | CHAR | 100 |  | Part of Object String |
| 5 | `OBJECT_STRING1` | CHAR | 100 |  | Part of Object String |
| 6 | `OBJECT_STRING2` | CHAR | 100 |  | Part of Object String |
| 7 | `OBJECT_STRING3` | CHAR | 100 |  | Part of Object String |
| 8 | `OBJECT_STRING4` | CHAR | 100 |  | Part of Object String |
| 9 | `EXPIRE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 10 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 11 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |

# ZISDMACTSPESTLOG
**Description:** Account specific estimation change log
**Total Fields:** 9
**Key Fields:** MANDT, TABLE_NAME, VKONT, FIELD_NAME, UDATE, UTIME

## Programs Using This Table
- `zisdm0255`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TABLE_NAME` | CHAR | 16 | 🔑 | Table name, 16 characters |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `FIELD_NAME` | CHAR | 60 | 🔑 | Explanatory Short Text |
| 5 | `UDATE` | DATS | 8 | 🔑 | Creation date of the change document |
| 6 | `UTIME` | TIMS | 6 | 🔑 | Time changed |
| 7 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 8 | `VALUE_OLD` | CHAR | 254 |  | Old contents of changed field |
| 9 | `VALUE_NEW` | CHAR | 254 |  | New contents of changed field |

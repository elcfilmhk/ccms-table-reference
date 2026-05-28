# ZISMDSPDEVICELOG
**Description:** change log of mapping between service point and meter
**Total Fields:** 11
**Key Fields:** MANDT, SERVICEPT, SERNR, AB, FIELD_NAME, ACTION, UDATE, UTIME

## Programs Using This Table
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERVICEPT` | CHAR | 50 | 🔑 | Point of delivery ID |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 5 | `FIELD_NAME` | CHAR | 60 | 🔑 | Explanatory Short Text |
| 6 | `ACTION` | CHAR | 20 | 🔑 | MDMS 20 Characters |
| 7 | `UDATE` | DATS | 8 | 🔑 | Creation date of the change document |
| 8 | `UTIME` | TIMS | 6 | 🔑 | Time changed |
| 9 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 10 | `VALUE_OLD` | CHAR | 254 |  | Old contents of changed field |
| 11 | `VALUE_NEW` | CHAR | 254 |  | New contents of changed field |

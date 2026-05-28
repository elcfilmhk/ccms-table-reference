# ZISDMLPEST_RPT
**Description:** Temporary table for ZISDM0241 to store report result
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, ANLAGE, TARIFNR, SERNR, MASSREAD, DATE_FROM, TIME_FROM

## Programs Using This Table
- `zisdm0241`
- `zisdm0241_sub`
- `zisdm0241n`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `TARIFNR` | CHAR | 10 | 🔑 | Rate key |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 7 | `DATE_FROM` | DATS | 8 | 🔑 | From-Date |
| 8 | `TIME_FROM` | TIMS | 6 | 🔑 | From-time |
| 9 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
| 10 | `VALUE` | DEC | 31 |  | Profile value at application level |

# ZISCS_SSR_HIST
**Description:** History table for ZISCS_SSR_CUST
**Total Fields:** 13
**Key Fields:** MANDT, GUID, VKONT, EVENT_ID, COUNTER, CREATED_ON, CREATED_AT

## Programs Using This Table
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisdm0371`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GUID` | RAW | 16 | 🔑 | Generic Data Element for GUID Fields (X16) |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EVENT_ID` | CHAR | 50 | 🔑 | Event ID from Autogrid |
| 5 | `COUNTER` | NUMC | 5 | 🔑 | Counter for SSR records |
| 6 | `CREATED_ON` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 7 | `CREATED_AT` | TIMS | 6 | 🔑 | Time |
| 8 | `FIELDNAME` | CHAR | 30 |  | Field Name |
| 9 | `OLD_VALUE` | CHAR | 30 |  | New contents of changed field |
| 10 | `NEW_VALUE` | CHAR | 30 |  | Old contents of changed field |
| 11 | `CHANGED_BY` | CHAR | 12 |  | Name of person who changed object |
| 12 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 13 | `CHANGED_AT` | TIMS | 6 |  | Time |

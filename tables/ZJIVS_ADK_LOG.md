# ZJIVS_ADK_LOG
**Description:** JiVS package: Log of ADK runs
**Total Fields:** 11
**Key Fields:** MANDT, CREAT_DATE, CREAT_TIME, DOCUMENT, ARCHIV_KEY

## Programs Using This Table
- `zjivs_export_adk`
- `zjivs_export_adk_dispatcher`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREAT_DATE` | DATS | 8 | 🔑 | Date of export run |
| 3 | `CREAT_TIME` | TIMS | 6 | 🔑 | Time of export run |
| 4 | `DOCUMENT` | CHAR | 6 | 🔑 | Archiving Session Number |
| 5 | `ARCHIV_KEY` | CHAR | 20 | 🔑 | Key for Archive File |
| 6 | `OBJECT` | CHAR | 10 |  | Archiving Object |
| 7 | `COUNT_OBJECTS` | DEC | 15 |  | Number of exported data objects |
| 8 | `COUNT_REC` | DEC | 15 |  | Number of exported data records |
| 9 | `COUNT_BYTES` | FLTP | 16 |  | Number of exported bytes |
| 10 | `MILLI_SECONDS` | DEC | 15 |  | Run time of export in milliseconds |
| 11 | `MESSAGE` | CHAR | 220 |  | JiVS - ADK message data element |

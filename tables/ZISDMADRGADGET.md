# ZISDMADRGADGET
**Description:** ADR Device Detail for Contract Account
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, MODEL, SERIAL_NUMBER

## Programs Using This Table
- `zisdm0366`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `MODEL` | CHAR | 30 | 🔑 | ADR Device Model details |
| 4 | `SERIAL_NUMBER` | CHAR | 18 | 🔑 | Device Serial Number |
| 5 | `DEVICE_ID` | CHAR | 50 |  | ADR Device model unique ID |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

# ZISDMSSRGADGET
**Description:** SSR Gadget details for contract account
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, MODEL, SERIAL_NUMBER

## Programs Using This Table
- `zisdm0366`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `MODEL` | CHAR | 30 | 🔑 | SSR Smart Gadget |
| 4 | `SERIAL_NUMBER` | CHAR | 18 | 🔑 | Device Serial Number |
| 5 | `BINDING` | CHAR | 2 |  | Gadget Binding details |
| 6 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

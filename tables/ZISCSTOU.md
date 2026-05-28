# ZISCSTOU
**Description:** TOU CA master
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, VERTRAG

## Programs Using This Table
- `ziscs0304`
- `ziscs0305`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AETIM` | CHAR | 4 |  | Last changed at |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

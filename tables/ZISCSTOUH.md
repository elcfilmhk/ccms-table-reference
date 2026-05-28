# ZISCSTOUH
**Description:** TOU CA time slice
**Total Fields:** 12
**Key Fields:** MANDT, VKONT, VERTRAG, BIS

## Programs Using This Table
- `ziscs0304`
- `ziscs0305`
- `zisdm0235`
- `zisdm0236`
- `zisdm0237`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `BIS` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 5 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 6 | `TOU_PLAN` | CHAR | 10 |  | TOU Plan |
| 7 | `PEAK_IND` | CHAR | 1 |  | Critical Peak Indicator |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AETIM` | CHAR | 4 |  | Last changed at |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

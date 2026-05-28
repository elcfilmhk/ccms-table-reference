# ZISMDSPDEVICE
**Description:** MDMS mapping between service point and meter
**Total Fields:** 10
**Key Fields:** MANDT, SERVICEPT, SERNR, AB

## Programs Using This Table
- `zisdm0127`
- `zisdm0185`
- `zismd0001`
- `zismd0005`
- `zismd0011`
- `zismd0030`
- `zismd0032`
- `zismd0033`
- `zismd0034`
- `zismd0035`
- `zismd0035_nov17`
- `zismd0036`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERVICEPT` | CHAR | 50 | 🔑 | Point of delivery ID |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 5 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

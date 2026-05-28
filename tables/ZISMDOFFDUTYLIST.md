# ZISMDOFFDUTYLIST
**Description:** Off-duty meter reader list
**Total Fields:** 9
**Key Fields:** MANDT, METER_READER_ID, EFFECTIVE_FROM, LEAVETYPE, TYPEDAYLEAVE

## Programs Using This Table
- `zismd0026`
- `zismd0029`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METER_READER_ID` | CHAR | 8 | 🔑 | Meter Reader ID |
| 3 | `EFFECTIVE_FROM` | DATS | 8 | 🔑 | Effective From |
| 4 | `LEAVETYPE` | CHAR | 10 | 🔑 | Leave Type |
| 5 | `TYPEDAYLEAVE` | CHAR | 4 | 🔑 | Type of Day Leave |
| 6 | `EFFECTIVE_TO` | DATS | 8 |  | Effective To |
| 7 | `OC_CODE` | CHAR | 2 |  | OC code |
| 8 | `UPDATEDATE` | DATS | 8 |  | Last Update |
| 9 | `UPDATEBY` | CHAR | 12 |  | Update By |

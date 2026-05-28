# ZISMDEXCLMRLIST
**Description:** Exclusive Meter reader list
**Total Fields:** 6
**Key Fields:** MANDT, METER_READER_ID, EFFECTIVE_FROM

## Programs Using This Table
- `zismd0026`
- `zismd0028`
- `zismd0029`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METER_READER_ID` | CHAR | 8 | 🔑 | Meter Reader ID |
| 3 | `EFFECTIVE_FROM` | DATS | 8 | 🔑 | Effective From |
| 4 | `EFFECTIVE_TO` | DATS | 8 |  | Effective To |
| 5 | `UPDATEDATE` | DATS | 8 |  | Last Update |
| 6 | `UPDATEBY` | CHAR | 12 |  | Update By |

# ZISMDSPMTRCOUNT
**Description:** Count of meter synchronized to MDMS from CCMS
**Total Fields:** 3
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zismd0007`
- `zismd0011`
- `zismd0025`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `METER_COUNT` | INT4 | 10 |  | Meter Count |

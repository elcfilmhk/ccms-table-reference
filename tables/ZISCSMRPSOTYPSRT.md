# ZISCSMRPSOTYPSRT
**Description:** Priority of SO Type for MRP interface ICS37
**Total Fields:** 3
**Key Fields:** MANDT, AUART

## Programs Using This Table
- `ziscs0106`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUART` | CHAR | 4 | 🔑 | Order Type |
| 3 | `PRIORITY` | DEC | 16 |  | Priority (less is higher. eg: 1 > 2) |

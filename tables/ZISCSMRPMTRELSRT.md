# ZISCSMRPMTRELSRT
**Description:** Priority of Meter Relationship for MRP interface ICS37
**Total Fields:** 3
**Key Fields:** MANDT, ZWZUART

## Programs Using This Table
- `ziscs0007_gprs`
- `ziscs0106`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWZUART` | NUMC | 2 | 🔑 | Register relationship type |
| 3 | `PRIORITY` | DEC | 16 |  | Priority (less is higher. eg: 1 > 2) |

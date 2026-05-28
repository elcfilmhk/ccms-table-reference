# ZISBIBTYPE
**Description:** Bill Type Table
**Total Fields:** 4
**Key Fields:** MANDT, SPRAS, ZZBILLID

## Programs Using This Table
- `zisbi0001`
- `zisbi0005`
- `zisbi0043`
- `zisbi0043n`
- `zisbi0136`
- `zisbi0205`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SPRAS` | LANG | 1 | 🔑 | Language Key |
| 3 | `ZZBILLID` | CHAR | 2 | 🔑 | Bill ID |
| 4 | `ZZIDTEXT` | CHAR | 40 |  | Bill Type / Sub Bill Type |

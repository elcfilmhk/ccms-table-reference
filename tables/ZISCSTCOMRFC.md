# ZISCSTCOMRFC
**Description:** Table for TCOM RFC destination
**Total Fields:** 3
**Key Fields:** MANDT, FUNCT

## Programs Using This Table
- `ziscs0111`
- `ziscs0116`
- `ziscs0123`
- `zisfi0347`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 3 | `RFCDEST` | CHAR | 32 |  | Logical destination (specified in function call) |

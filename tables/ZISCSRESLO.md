# ZISCSRESLO
**Description:** Load-restricited Connection Object Maintenance
**Total Fields:** 8
**Key Fields:** MANDT, CONNOBJ

## Programs Using This Table
- `ziscs0199`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONNOBJ` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `REGION` | CHAR | 15 |  | Region |
| 4 | `OC` | CHAR | 2 |  | Operation Centre |
| 5 | `SUBSTATION` | CHAR | 6 |  | Substation Number |
| 6 | `ADDRESS` | CHAR | 100 |  | Address of the Connection Object |
| 7 | `SUPPLYPOINT` | CHAR | 20 |  | Supply Point |
| 8 | `REASON` | CHAR | 100 |  | Load-restricted Reason |

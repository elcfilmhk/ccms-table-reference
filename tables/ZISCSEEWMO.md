# ZISCSEEWMO
**Description:** Custom Order Data
**Total Fields:** 16
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0110`
- `ziscs0115`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ORDER_CODE` | CHAR | 4 |  | Order Code |
| 2 | `IWERK` | CHAR | 4 |  | Maintenance Planning Plant |
| 3 | `VAWRK` | CHAR | 4 |  | Plant associated with main work center |
| 4 | `VAPLZ` | CHAR | 8 |  | Main work center for maintenance tasks |
| 5 | `SPRAS` | LANG | 1 |  | Language Key |
| 6 | `AUART` | CHAR | 4 |  | Order Type |
| 7 | `CUOBJ` | NUMC | 18 |  | Configuration (internal object number) |
| 8 | `GSTRP` | DATS | 8 |  | Basic start date |
| 9 | `GLTRP` | DATS | 8 |  | Basic finish date |
| 10 | `GSUZP` | TIMS | 6 |  | Basic Start (Time) |
| 11 | `GLUZP` | TIMS | 6 |  | Basic finish (time) |
| 12 | `BZGSOBJTYP` | CHAR | 2 |  | Technical reference object type |
| 13 | `BZGSOBJ` | CHAR | 30 |  | Technical reference object |
| 14 | `BZGSERNR` | CHAR | 18 |  | Serial Number |
| 15 | `DARK_CONF` | CHAR | 1 |  | Configuration in the background |
| 16 | `KUNUM` | CHAR | 10 |  | Customer Number |

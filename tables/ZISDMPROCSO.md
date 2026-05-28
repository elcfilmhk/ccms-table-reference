# ZISDMPROCSO
**Description:** Structure for service order processing
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0050`
- `zisdm0051`
- `zisdm0175`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `AUFNR` | CHAR | 12 |  | Order Number |
| 2 | `TEXT` | CHAR | 255 |  | Text Line |
| 3 | `BP_COMP` | CHAR | 1 |  | Action |
| 4 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 5 | `VAPLZ` | CHAR | 8 |  | Main work center for maintenance tasks |
| 6 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 7 | `AUART` | CHAR | 4 |  | Order Type |
| 8 | `GSTRP` | DATS | 8 |  | Basic start date |
| 9 | `GLTRP` | DATS | 8 |  | Basic finish date |
| 10 | `PRIOK` | CHAR | 1 |  | Priority |
| 11 | `PARTNER` | CHAR | 17 |  | Partner number |

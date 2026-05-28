# ZZISCSBULK
**Description:** Customized structure - Bulk installation/removal/replacement
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0015`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `ANLAGE` | CHAR | 10 |  | Installation |
| 3 | `ACT_DATE` | DATS | 8 |  | Activity date |
| 4 | `MTR_ROLE` | CHAR | 30 |  | Meter Role |
| 5 | `MTR_RDG` | CHAR | 36 |  | Expected meter reading in screen format |
| 6 | `MARK_LOST` | CHAR | 1 |  | Yes/no |
| 7 | `ACT_REASON` | CHAR | 2 |  | Activity reason |
| 8 | `OLD_SERNR` | CHAR | 18 |  | Serial Number |
| 9 | `MATNR` | CHAR | 18 |  | Material Number |
| 10 | `MULTIPLE` | CHAR | 1 |  | 'X' - Multiple meter reading exist |
| 11 | `MULTI_MTR_RDG` | TTYP | 0 |  | Multiple meter reading storage |

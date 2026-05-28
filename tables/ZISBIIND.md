# ZISBIIND
**Description:** Indicator for the bar chart
**Total Fields:** 7
**Key Fields:** MANDT, ANLAGE, AB

## Programs Using This Table
- `zisbi_upd_ind`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 4 | `FLAG` | CHAR | 1 |  | Single-Character Flag |
| 5 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |

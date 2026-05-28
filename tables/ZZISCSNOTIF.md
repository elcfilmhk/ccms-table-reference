# ZZISCSNOTIF
**Description:** Structure for BOR service order notifications
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `zdiscon`
- `zisbi0173`
- `zisbi0198`
- `ziscs0256`
- `ziscs0297`
- `zisuorder`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MNCOD` | CHAR | 4 |  | Task Code |
| 2 | `PSTER` | DATS | 8 |  | Planned Start Date |
| 3 | `PSTUR` | TIMS | 6 |  | Planned Start Time for Task |
| 4 | `PETER` | DATS | 8 |  | Planned finish date |
| 5 | `PETUR` | TIMS | 6 |  | Planned Finish Time for Task |
| 6 | `MATXT` | CHAR | 40 |  | Short Text for Task |
| 7 | `MNGFA` | NUMC | 3 |  | Quantity Factor for Activities |

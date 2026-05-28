# ZISBIAPPLOG
**Description:** Approvers for manaul bill
**Total Fields:** 6
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `APNAM` | CHAR | 12 |  | Approver Name |
| 6 | `APDAT` | DATS | 8 |  | Date Approved |

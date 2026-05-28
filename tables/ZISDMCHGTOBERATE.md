# ZISDMCHGTOBERATE
**Description:** Mass Change To Be Reprogram Rate ID
**Total Fields:** 6
**Key Fields:** RUNDATE, REPRGRATEID

## Programs Using This Table
- `zisdm0016`
- `zisdm0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RUNDATE` | DATS | 8 | 🔑 | Date |
| 2 | `REPRGRATEID` | CHAR | 8 | 🔑 | The ID of the re-program rate |
| 3 | `NEWREPRGRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 4 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 5 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 6 | `PROCESSEDINDC` | CHAR | 1 |  | Processed_Indc |

# ZISBIRVLOG
**Description:** Log of reversed invoice using bill reversal workflow
**Total Fields:** 7
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `ERNAM` | CHAR | 12 |  | Requester Name / Workflow Initiator |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `APNAM` | CHAR | 12 |  | Approver Name |
| 6 | `APDAT` | DATS | 8 |  | Date Approved |
| 7 | `REVFLAG` | CHAR | 1 |  | Reversal Success Flag (WF Auto Execution) |

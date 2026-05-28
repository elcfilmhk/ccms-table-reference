# ZISDMIVRC
**Description:** Rate Category Dependent Settings
**Total Fields:** 13
**Key Fields:** CLIENT, TARIFTYP

## Programs Using This Table
- `zcl_iv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `ZZISIVRCTP` | CHAR | 1 |  | Flag: Rate Category Type is BULK/LPT |
| 4 | `ZZISIV0CON` | DEC | 5 |  | Zero-Consumption Threshold Level |
| 5 | `ZZISIVNRCT` | DEC | 5 |  | Not Rep Consumption Threshold Level |
| 6 | `ZZISIVMINP` | DEC | 3 |  | Minimum Portion of MR Cycle |
| 7 | `ZZISIVSDHI` | DEC | 2 |  | IV Standard Deviation High Limit |
| 8 | `ZZISIVSDLO` | DEC | 2 |  | IV Standard Deviation Low Limit |
| 9 | `ZZISIV06PC` | DEC | 3 |  | IV06: Last Consumption Threshold |
| 10 | `ZZISIV06CR` | DEC | 3 |  | IV06: Consumption Ratio Threshold |
| 11 | `ZZISIV15MP` | DEC | 3 |  | IV15: Minimum Percentage for Round Clock Reading |
| 12 | `ZZISIV15VR` | DEC | 4 |  | IV15: Treshold for Visual Read Error |
| 13 | `ZZISIVDFMI` | DEC | 3 |  | Max. Number of Days Between Move-In and Current Reading Date |

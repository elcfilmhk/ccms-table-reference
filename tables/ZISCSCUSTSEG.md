# ZISCSCUSTSEG
**Description:** Customer creditworthiness segmentation
**Total Fields:** 9
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0079`
- `zisbi0080`
- `ziscs0130`
- `ziscs0151`
- `ziscs0152`
- `ziscs0163`
- `ziscs0164`
- `ziscs0195`
- `ziscs0467`
- `zisfi0101`
- `zisfi0116`
- `zisfi0116_1`
- `zisfi0116_test`
- `zisfi0116_test2`
- `zisfi0116_test3`
- `zisfi0120`
- `zisfi0123`
- `zisfi0131`
- `zisfi0137`
- `zisfi0146`
- `zisfi0150`
- `zisfi0155`
- `zisfi0156`
- `zisfi0157`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SEGMENT_LABEL` | CHAR | 1 |  | Segment label |
| 4 | `INITIAL_SCORE` | DEC | 17 |  | Initial Score |
| 5 | `CONFID_LEVEL` | DEC | 17 |  | Confidence level |
| 6 | `SCORE_LABEL` | CHAR | 10 |  | Score label |
| 7 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 9 | `CREDIT_SCORE` | DEC | 17 |  | Account Credit Score |

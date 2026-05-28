# ZISFIDDREJACT
**Description:** DD Reject Follow Up Action
**Total Fields:** 6
**Key Fields:** MANDT, SDDA_CODE

## Programs Using This Table
- `zisfi0241`
- `zisfi0276`
- `ztest_zisfi0276`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SDDA_CODE` | CHAR | 2 | 🔑 | SDDA code |
| 3 | `REJECT_REASON` | CHAR | 25 |  | Reject reason |
| 4 | `SUGT_FOLLOWUP1` | CHAR | 132 |  | First note text line |
| 5 | `SUGT_FOLLOWUP2` | CHAR | 132 |  | First note text line |
| 6 | `SUGT_FOLLOWUP3` | CHAR | 132 |  | First note text line |

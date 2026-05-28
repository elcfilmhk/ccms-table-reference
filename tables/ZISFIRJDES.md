# ZISFIRJDES
**Description:** Reject reasons for return letter
**Total Fields:** 5
**Key Fields:** MANDT, RLGRD, RLHBK

## Programs Using This Table
- `zisfi0161`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RLGRD` | CHAR | 3 | 🔑 | Return Reason |
| 3 | `RLHBK` | CHAR | 6 | 🔑 | House bank's return reason |
| 4 | `ENG_DESC` | CHAR | 80 |  | English Description |
| 5 | `CHI_DESC` | CHAR | 80 |  | Chinese Description |

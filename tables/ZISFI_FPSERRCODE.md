# ZISFI_FPSERRCODE
**Description:** FPS Refund HSBC Error Code
**Total Fields:** 4
**Key Fields:** MANDT, RLHBK

## Programs Using This Table
- `zisfi0334`
- `zisfi0341`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RLHBK` | CHAR | 6 | 🔑 | House bank's return reason |
| 3 | `RTEXT` | CHAR | 50 |  | Name of Returns Reason |
| 4 | `AUTO_CHEQUE` | CHAR | 1 |  | Auto cheque |

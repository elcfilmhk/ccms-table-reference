# ZISDMINCENTSCH
**Description:** Incentive Scheme
**Total Fields:** 7
**Key Fields:** MANDT, TPLNR, INCENT_PERIOD, TARGET_SEQNO

## Programs Using This Table
- `zisdm0218`
- `zisdm0221`
- `zisdm0222`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TPLNR` | CHAR | 30 | 🔑 | Functional Location |
| 3 | `INCENT_PERIOD` | NUMC | 2 | 🔑 | Incentive Period |
| 4 | `TARGET_SEQNO` | NUMC | 2 | 🔑 | Target Sequence Number |
| 5 | `TARGET_LOWER_LIM` | DEC | 5 |  | Lower limit of Target % |
| 6 | `TARGET_UPPER_LIM` | DEC | 5 |  | Upper limit of Target % |
| 7 | `INCENT_AMT` | DEC | 5 |  | Incentive amount |

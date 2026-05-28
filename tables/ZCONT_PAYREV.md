# ZCONT_PAYREV
**Description:** Payment Condition Suppress
**Total Fields:** 4
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `zisfi0200`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `PAYCONDSUPPRESS` | CHAR | 1 |  | Payment Condition Suppress |

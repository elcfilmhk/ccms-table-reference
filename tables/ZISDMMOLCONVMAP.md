# ZISDMMOLCONVMAP
**Description:** Mapping for New Register Group & New Device Category
**Total Fields:** 5
**Key Fields:** MANDT, MATNR, ZWGRUPPE

## Programs Using This Table
- `zisdm0216`
- `zisdm0229`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MATNR` | CHAR | 18 | 🔑 | Device category |
| 3 | `ZWGRUPPE` | CHAR | 8 | 🔑 | Register Group |
| 4 | `NEW_ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 5 | `NEW_MATNR` | CHAR | 18 |  | Device category |

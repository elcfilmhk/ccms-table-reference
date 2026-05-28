# ZISCEP_EHER_LINK
**Description:** CEP - e-HER (Config Table - Links)
**Total Fields:** 5
**Key Fields:** MANDT, LINK_IDENTIFIER, SYSTEM_TYPE

## Programs Using This Table
- `ziscs0457`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LINK_IDENTIFIER` | CHAR | 40 | 🔑 | CEP: e-HER Link Identifier |
| 3 | `SYSTEM_TYPE` | CHAR | 1 | 🔑 | CEP: e-HER (System Type) |
| 4 | `ORIGINAL_LINK` | CHAR | 255 |  | CEP: e-HER (Original Link) |
| 5 | `NEW_LINK` | CHAR | 255 |  | CEP: e-HER (New Link) |

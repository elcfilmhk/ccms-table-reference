# ZISMDSPCREGISTER
**Description:** Service Point Channel assignment for non-standard meter
**Total Fields:** 6
**Key Fields:** MANDT, ZWGRUPPE, ZWNUMMER, INTERVAL_CHANNEL

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWGRUPPE` | CHAR | 8 | 🔑 | Register Group |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `INTERVAL_CHANNEL` | CHAR | 1 | 🔑 | X: Interval Channel; Otherwise:Register Channel |
| 5 | `SP_CHANNEL` | NUMC | 5 |  | Service Point Channel |
| 6 | `SHORTCUT_CODE` | CHAR | 30 |  | Shortcut code for the register channel |

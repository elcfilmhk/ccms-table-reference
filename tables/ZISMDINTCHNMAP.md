# ZISMDINTCHNMAP
**Description:** Mapping table of Interval Channel Number
**Total Fields:** 8
**Key Fields:** MANDT, HERST, TYPBZ, ZWNUMMER

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0012`
- `zismd0023`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 3 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `INT_CHANNEL_NO` | NUMC | 3 |  | Interval Channel Number |
| 6 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 7 | `SHORTCUTCODE_LP` | CHAR | 30 |  | Shortcut code for the register channel |
| 8 | `SHORTCUTCD_NOLP` | CHAR | 30 |  | Shortcut code for the register channel |

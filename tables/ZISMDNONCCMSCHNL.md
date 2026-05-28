# ZISMDNONCCMSCHNL
**Description:** Meters not in CCMS Channel
**Total Fields:** 18
**Key Fields:** MANDT, HERST, TYPBZ, ZWNUMMER, SP_CHANNEL_NO

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0015`
- `zismd0024`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 3 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `SP_CHANNEL_NO` | NUMC | 5 | 🔑 | Service Point Channel |
| 6 | `DISPLAY_CODE` | CHAR | 2 |  | Display Code |
| 7 | `STANZVORNAC` | NUMC | 2 |  | Total number of dial of the register |
| 8 | `STANZNAC` | NUMC | 2 |  | Places after the decimal in a register |
| 9 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 10 | `DESCRIPTION` | CHAR | 100 |  | Description of Non CCMS Channel Register |
| 11 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 12 | `SEQUENCE` | NUMC | 4 |  | Sequence of meter in the route |
| 13 | `READ_TYPE_CODE` | CHAR | 16 |  | Read Type Code |
| 14 | `DISP_MULTIPLIER` | NUMC | 4 |  | Display Multiplier |
| 15 | `REGDEC_NAMETYPE` | CHAR | 50 |  | Register Decode Name Type of register |
| 16 | `ZWFAKT` | DEC | 12 |  | Register factor |
| 17 | `SHORTCUT_CODE` | CHAR | 30 |  | Shortcut code for the register channel |
| 18 | `SKIP_RECDEV` | CHAR | 1 |  | Skip Creating Link to Recording Device |

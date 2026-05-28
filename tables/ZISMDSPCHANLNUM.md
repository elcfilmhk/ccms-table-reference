# ZISMDSPCHANLNUM
**Description:** Service Point Channel Number Mapping
**Total Fields:** 8
**Key Fields:** MANDT, ZWART, ZWTYP, BLIWIRK, MASSREAD, INTERVAL_CHANNEL

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0023`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWART` | CHAR | 2 | 🔑 | Register type |
| 3 | `ZWTYP` | NUMC | 2 | 🔑 | Register category |
| 4 | `BLIWIRK` | NUMC | 2 | 🔑 | Reactive, apparent, or active registers |
| 5 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 6 | `INTERVAL_CHANNEL` | CHAR | 1 | 🔑 | X: Interval Channel; Otherwise:Register Channel |
| 7 | `SP_CHANNEL` | NUMC | 5 |  | Service Point Channel |
| 8 | `SHORTCUT_CODE` | CHAR | 30 |  | Shortcut code for the register channel |

# ZISMDPULSEMULTI
**Description:** Pulse Multiplier
**Total Fields:** 4
**Key Fields:** MANDT, HERST, TYPBZ

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 3 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `PULSE_MULTIPLIER` | NUMC | 4 |  | KE Pulse Multiplier of the Interval Channel |

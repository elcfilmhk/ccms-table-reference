# ZISEDERROR
**Description:** EDM - Error table for formula creation
**Total Fields:** 3
**Key Fields:** MANDT, CODE

## Programs Using This Table
- `zedm_delta_housekeeping`
- `zedm_delta_housekeeping_sub`
- `zedm_ext_30int_dynamic`
- `zedm_ext_30int_sub`
- `zised0005`
- `zised0016`
- `zised0023`
- `zised0025`
- `zised0030`
- `zised0053`
- `zised0054`
- `zised0055`
- `zised0065`
- `zised0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CODE` | CHAR | 4 | 🔑 | EDM Message Code |
| 3 | `TEXT` | CHAR | 255 |  | EDM - Message Text |

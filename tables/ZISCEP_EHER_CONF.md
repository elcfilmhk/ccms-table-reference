# ZISCEP_EHER_CONF
**Description:** CEP - e-HER (Config Table - store URL / Open Tracking links)
**Total Fields:** 6
**Key Fields:** MANDT, TRACK_IDENTIFIER, SYSTEM_TYPE

## Programs Using This Table
- `ziscs0457`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRACK_IDENTIFIER` | CHAR | 40 | 🔑 | CEP: e-HER Tracking Link Identifier |
| 3 | `SYSTEM_TYPE` | CHAR | 1 | 🔑 | CEP: e-HER (System Type) |
| 4 | `TRACK_LINK` | CHAR | 255 |  | CEP: e-HER Tracking Link |
| 5 | `PARAMETER_1` | CHAR | 32 |  | CEP: e-HER Tracking Parameter 1 |
| 6 | `PARAMETER_2` | CHAR | 32 |  | CEP: e-HER Tracking Parameter 2 |

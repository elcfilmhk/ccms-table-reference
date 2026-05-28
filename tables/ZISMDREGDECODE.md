# ZISMDREGDECODE
**Description:** Map the decoded register value from the MV90 register decode
**Total Fields:** 5
**Key Fields:** MANDT, HERST, TYPBZ, ZWNUMMER

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0017`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 3 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `REGDEC_NAMETYPE` | CHAR | 50 |  | Register Decode Name Type of register |

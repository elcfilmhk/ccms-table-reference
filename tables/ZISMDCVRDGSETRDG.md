# ZISMDCVRDGSETRDG
**Description:** Populate reading from register to another register
**Total Fields:** 5
**Key Fields:** MANDT, HERST, TYPBZ, FR_REG

## Programs Using This Table
- `zismd0009`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 3 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `FR_REG` | NUMC | 3 | 🔑 | Register |
| 5 | `TO_REG` | NUMC | 3 |  | Register |

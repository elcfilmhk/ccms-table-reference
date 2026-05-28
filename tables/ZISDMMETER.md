# ZISDMMETER
**Description:** Meter Table
**Total Fields:** 6
**Key Fields:** MANDT, GERNR

## Programs Using This Table
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0039`
- `zisdm0056`
- `zisdm0075`
- `zisdm0090`
- `zisdm0091`
- `zisdm0098`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `EQART` | CHAR | 10 |  | Type of Technical Object |
| 4 | `GROES` | CHAR | 32 |  | Size/dimensions |
| 5 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 6 | `BRGEW` | CHAR | 25 |  | Inventory number |

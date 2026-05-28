# ZISDMFACTOR
**Description:** Customized table for primary voltage factor
**Total Fields:** 3
**Key Fields:** MANDT, INVNR

## Programs Using This Table
- `zisdm0022_bulk`
- `zisdm0052`
- `zisdmupld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INVNR` | CHAR | 25 | 🔑 | Inventory number |
| 3 | `ZZFACTOR` | INT2 | 5 |  | Mulyiplying Factor |

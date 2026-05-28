# ZISCSCTRREG
**Description:** Main Working Center and Region mapping
**Total Fields:** 4
**Key Fields:** MANDT, MAIN_WK_CTR

## Programs Using This Table
- `ziscs0200`
- `zisdm0401`
- `zisfi0242_d`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAIN_WK_CTR` | CHAR | 8 | 🔑 | Main work center for maintenance tasks |
| 3 | `DESCRIPTION` | CHAR | 50 |  | Work Center Description |
| 4 | `REGION` | CHAR | 15 |  | Region |

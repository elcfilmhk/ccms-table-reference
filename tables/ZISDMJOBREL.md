# ZISDMJOBREL
**Description:** Specific Consumption for Different Rate Category
**Total Fields:** 5
**Key Fields:** MANDT, RATECAT

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`
- `zisdm0170`
- `zisdm0172`
- `zisdm0176`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RATECAT` | CHAR | 10 | 🔑 | Rate category |
| 3 | `ZEROCONSMP` | DEC | 10 |  | Zero Consumption |
| 4 | `NOTREPCSMP` | DEC | 10 |  | Not Rep. Consumption |
| 5 | `IV15_PERCENT` | DEC | 3 |  | IV15 Percentage |

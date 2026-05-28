# ZISDMTEMPT
**Description:** Customized table for Daily Maximum Temperature
**Total Fields:** 3
**Key Fields:** MANDT, ADAT

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 3 | `ZZTEMPTURE` | DEC | 6 |  | Temperature |

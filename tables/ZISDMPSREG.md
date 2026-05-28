# ZISDMPSREG
**Description:** Power System Operation Centre and Region Mapping Table
**Total Fields:** 4
**Key Fields:** MANDT, ZEWMPLANTSEC

## Programs Using This Table
- `zisdm0019`
- `zisdm0021`
- `zisdm0023`
- `zisdm0024`
- `zisdm0036`
- `zisdm0058`
- `zisdm0080`
- `zisdm0089`
- `zisdm0119`
- `zisdm0139`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZEWMPLANTSEC` | CHAR | 2 | 🔑 | EWMS Plant Section (Operation Centre of the Power System) |
| 3 | `ZPSREGION` | CHAR | 2 |  | Region of Power System |
| 4 | `ZRPREGION` | CHAR | 3 |  | Region of Revenue Protection Branch of Metering Department |

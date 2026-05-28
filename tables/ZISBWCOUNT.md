# ZISBWCOUNT
**Description:** RPISU BW Count
**Total Fields:** 12
**Key Fields:** MANDT, RPDAT, CRDAT, TPDAT, OBJCT, CNTRL, CNVAL

## Programs Using This Table
- `zisbw0010`
- `zisbw0011`
- `zisbw0012`
- `zisbw0013`
- `zisbw0014`
- `zisbw0015`
- `zisbw0016`
- `zisbw0017`
- `zisbw0018`
- `zisbw0020`
- `zisbw0021`
- `zisbw0043`
- `zisbw0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPDAT` | DATS | 8 | 🔑 | Report date |
| 3 | `CRDAT` | DATS | 8 | 🔑 | Create from |
| 4 | `TPDAT` | DATS | 8 | 🔑 | Create to |
| 5 | `OBJCT` | CHAR | 12 | 🔑 | Object |
| 6 | `CNTRL` | CHAR | 12 | 🔑 | Control field |
| 7 | `CNVAL` | CHAR | 50 | 🔑 | Control value |
| 8 | `DESCR` | CHAR | 50 |  | BW count description |
| 9 | `BWCNT` | NUMC | 9 |  | BW Count |
| 10 | `RFTIM` | CHAR | 14 |  | BW count reference timestamp |
| 11 | `BWAMT` | DEC | 15 |  | Amount |
| 12 | `BWAMT2` | DEC | 25 |  | Amount 2 |

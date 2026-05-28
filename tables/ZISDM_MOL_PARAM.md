# ZISDM_MOL_PARAM
**Description:** MOL Param Table
**Total Fields:** 12
**Key Fields:** MANDT, VKONTO, SERNR, OPGROUP, EFFFROM, EFFTO

## Programs Using This Table
- `zisdm0286`
- `zisdm0287`
- `zisdm0295`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `OPGROUP` | CHAR | 10 | 🔑 | Operating time groups |
| 5 | `EFFFROM` | DATS | 8 | 🔑 | MOL Effective From Date |
| 6 | `EFFTO` | DATS | 8 | 🔑 | MOL Effective To Date |
| 7 | `A` | DEC | 31 |  | A |
| 8 | `B` | DEC | 31 |  | B |
| 9 | `C` | DEC | 31 |  | C |
| 10 | `R` | DEC | 31 |  | R sq |
| 11 | `DATAFROM` | DATS | 8 |  | MOL Dataset From |
| 12 | `DATATO` | DATS | 8 |  | MOL Dataset To |

# ZISDM_MOL_KWH
**Description:** Monthly kWh Table
**Total Fields:** 6
**Key Fields:** MANDT, VKONTO, SERNR, OPGROUP, KWH_MONTH

## Programs Using This Table
- `zisdm0286`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `OPGROUP` | CHAR | 10 | 🔑 | Operating time groups |
| 5 | `KWH_MONTH` | DATS | 8 | 🔑 | Date |
| 6 | `KWH_AVG` | DEC | 31 |  | MOL equation parameters |

# ZISDMADRCUAPPDCC
**Description:** ADR Customer CA/Meter
**Total Fields:** 7
**Key Fields:** MANDT, DRCUSTNO, VKONTO, SERNR

## Programs Using This Table
- `zisdm0309`
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ACTION` | CHAR | 1 |  | DR Customer information update type method |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

# ZISDMADRCUCAPDCC
**Description:** ADR Customer Checking CA list
**Total Fields:** 6
**Key Fields:** MANDT, DRCUSTNO, VKONTO

## Programs Using This Table
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ACTION` | CHAR | 1 |  | DR Customer information update type method |
| 5 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 6 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

# ZISDMADRCUSTCKAP
**Description:** ADR Customer checking CA list
**Total Fields:** 3
**Key Fields:** MANDT, DRCUSTNO, VKONTO

## Programs Using This Table
- `zisdm0310_adr`
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |

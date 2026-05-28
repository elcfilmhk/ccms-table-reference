# ZISBI_GS_CA
**Description:** Eligibility CA for Government Subsidy
**Total Fields:** 7
**Key Fields:** MANDT, SCHEME, VKONT

## Programs Using This Table
- `zisbi0259`
- `zisfi0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME` | CHAR | 6 | 🔑 | Scheme |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `REMARK` | CHAR | 40 |  | Remark |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 7 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |

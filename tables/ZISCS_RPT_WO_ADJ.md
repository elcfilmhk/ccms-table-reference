# ZISCS_RPT_WO_ADJ
**Description:** Government entitlement report without adjustment
**Total Fields:** 12
**Key Fields:** MANDT, VKONT, REFMTH

## Programs Using This Table
- `ziscs0222`
- `ziscs0223`
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226f`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REFMTH` | DATS | 8 | 🔑 | Entitlement ref month |
| 4 | `CPUDT` | DATS | 8 |  | Date of entry |
| 5 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 6 | `STATUS` | CHAR | 1 |  | Entitlement month status |
| 7 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 8 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 9 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 10 | `BCLCHG` | DATS | 8 |  | Billing class change date |
| 11 | `ITXDT` | DATS | 8 |  | Input transaction date |
| 12 | `ITXTM` | TIMS | 6 |  | Input transaction time |

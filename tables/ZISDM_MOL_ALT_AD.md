# ZISDM_MOL_ALT_AD
**Description:** MOL Alert Email Address
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, SERNR, SEQNR

## Programs Using This Table
- `zisdm0293`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `SEQNR` | NUMC | 3 | 🔑 | Email Alert Sequence No. |
| 5 | `CAFLAG` | CHAR | 1 |  | Flag to select Contract Accounts |
| 6 | `.INCLUDE` | &nbsp; | 0 |  | MOL Alert Email Strcuture |
| 7 | `EMAIL_ADDRESS` | CHAR | 241 |  | E-Mail Address |

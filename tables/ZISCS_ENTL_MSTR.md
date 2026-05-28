# ZISCS_ENTL_MSTR
**Description:** Entitlement master
**Total Fields:** 7
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zccgvt10`
- `zisbi0019`
- `ziscs0218`
- `ziscs0243`
- `ziscs0244`
- `ziscs0251`
- `ziscs0540`
- `ziscs0831`
- `ziscs0859`
- `ziscsgovsubmreverse`
- `zisfi0271`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 4 | `CPUDT` | DATS | 8 |  | Date of entry |
| 5 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 6 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 7 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |

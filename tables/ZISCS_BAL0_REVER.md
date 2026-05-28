# ZISCS_BAL0_REVER
**Description:** Government entitlement zero balance reverse
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, RVZDAT

## Programs Using This Table
- `ziscs0225`
- `ziscsgsrptreset`
- `zisfi0260`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `RVZDAT` | DATS | 8 | 🔑 | Reverse zero batch date |
| 4 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 5 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 6 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 7 | `CREATE_DATE` | DATS | 8 |  | Date of entry |
| 8 | `CREATE_TIME` | TIMS | 6 |  | Time of Entry |

# ZISCS_BAL0_REVES
**Description:** Government entitlement zero balance reverse
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, RVZDAT, SCHEME

## Programs Using This Table
- `ziscs0225`
- `ziscs0226`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `RVZDAT` | DATS | 8 | 🔑 | Reverse zero batch date |
| 4 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 5 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 6 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 7 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 8 | `CREATE_DATE` | DATS | 8 |  | Date of entry |
| 9 | `CREATE_TIME` | TIMS | 6 |  | Time of Entry |

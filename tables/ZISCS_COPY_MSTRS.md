# ZISCS_COPY_MSTRS
**Description:** Entitlement Master Snapshot for Reporting New
**Total Fields:** 12
**Key Fields:** MANDT, RUNDT, VKONT, SCHEME

## Programs Using This Table
- `ziscs0218`
- `ziscs0225`
- `ziscs0226`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch Run Date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 5 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 6 | `CPUDT` | DATS | 8 |  | Date of entry |
| 7 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 8 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 9 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 10 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 11 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 12 | `UPDATED` | CHAR | 1 |  | Updated Indicator |

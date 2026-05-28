# ZISCS_COPY_MSTR
**Description:** Entitlement Master Snapshot for Reporting
**Total Fields:** 11
**Key Fields:** MANDT, RUNDT, VKONT

## Programs Using This Table
- `ziscs0218`
- `ziscs0225`
- `ziscs0360`
- `ziscs0362`
- `zisfi0260`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch Run Date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 5 | `CPUDT` | DATS | 8 |  | Date of entry |
| 6 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 7 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 8 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 9 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 10 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 11 | `UPDATED` | CHAR | 1 |  | Updated Indicator |

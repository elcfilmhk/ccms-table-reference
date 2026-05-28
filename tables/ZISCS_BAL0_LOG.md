# ZISCS_BAL0_LOG
**Description:** Zero balance extra log for report zero indicator
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, RPZDAT

## Programs Using This Table
- `ziscs0225`
- `ziscs0362`
- `zisfi0260`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `RPZDAT` | DATS | 8 | 🔑 | Report zero (balance zero during reporting) batch date |
| 4 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 5 | `CPUDT` | DATS | 8 |  | Subsidy last change date |
| 6 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 7 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 8 | `BCLCHG` | DATS | 8 |  | Billing class change date |
| 9 | `CREATE_DATE` | DATS | 8 |  | Date of entry |
| 10 | `CREATE_TIME` | TIMS | 6 |  | Time of Entry |

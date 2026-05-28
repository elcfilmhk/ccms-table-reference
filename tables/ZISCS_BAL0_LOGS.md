# ZISCS_BAL0_LOGS
**Description:** Zero balance extra log for report zero indicator
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, SCHEME, RPZDAT

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
| 3 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 4 | `RPZDAT` | DATS | 8 | 🔑 | Report zero (balance zero during reporting) batch date |
| 5 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 6 | `CPUDT` | DATS | 8 |  | Subsidy last change date |
| 7 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 8 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 9 | `BCLCHG` | DATS | 8 |  | Billing class change date |
| 10 | `CREATE_DATE` | DATS | 8 |  | Date of entry |
| 11 | `CREATE_TIME` | TIMS | 6 |  | Time of Entry |

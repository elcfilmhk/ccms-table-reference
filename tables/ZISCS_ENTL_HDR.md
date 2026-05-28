# ZISCS_ENTL_HDR
**Description:** Entitlement Master Tracking Table
**Total Fields:** 15
**Key Fields:** MANDT, ANLAGE, VKONT, REFMTH

## Programs Using This Table
- `ziscs0219`
- `ziscs0223`
- `ziscs0244`
- `ziscs0251`
- `ziscs0292`
- `ziscs0342`
- `ziscs0831`
- `ziscsgovsubmreverse`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `REFMTH` | DATS | 8 | 🔑 | Entitlement ref month |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 7 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 8 | `ERNAM` | CHAR | 12 |  | Created By |
| 9 | `CPUDT` | DATS | 8 |  | Date of entry |
| 10 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 11 | `CUMENT` | CURR | 13 |  | Entitlement grant |
| 12 | `ENTREV` | CHAR | 1 |  | Entitlement rev |
| 13 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 14 | `BCLCHG` | DATS | 8 |  | Billing class change date |
| 15 | `MDFTS` | CHAR | 14 |  | Modified timestamp |

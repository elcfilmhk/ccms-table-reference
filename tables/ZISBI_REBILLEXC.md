# ZISBI_REBILLEXC
**Description:** Exceptional list which output contract account
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, ANLAGE, ERROR_DAT, ERROR_TIME

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_1`
- `zisbi0042_2`
- `zisbi0042_newfm`
- `zisbi0260`
- `zisbi0266`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `ERROR_DAT` | DATS | 8 | 🔑 | Error  Date |
| 5 | `ERROR_TIME` | TIMS | 6 | 🔑 | Error Time |
| 6 | `ERRCODE` | CHAR | 2 |  | Error Code |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `EXT_ID` | CHAR | 100 |  | Application Log: External ID |
| 9 | `BATCHONLN` | CHAR | 1 |  | Batch or Online for rebill/reverse status |

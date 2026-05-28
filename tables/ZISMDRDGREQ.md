# ZISMDRDGREQ
**Description:** Meter Reading Required to Synchronize to MDMS from CCMS
**Total Fields:** 6
**Key Fields:** MANDT, GERNR, ANLAGE, ABLESGR, ADAT, BATCH_RUN_DATE

## Programs Using This Table
- `zismd0009`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 5 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 6 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch Run Date |

# ZISDMEV_MIG_LOG
**Description:** Migration Log
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, ANLAGE, SERNR, ZWNUMMER, COUNTER, LOG_DATE, LOG_UZEIT

## Programs Using This Table
- `zcl_isdm_evtou_mig_rpt`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 6 | `COUNTER` | NUMC | 4 | 🔑 | Counter |
| 7 | `LOG_DATE` | DATS | 8 | 🔑 | Date |
| 8 | `LOG_UZEIT` | TIMS | 6 | 🔑 | Time |
| 9 | `LOG_STATUS` | CHAR | 220 |  | Message |

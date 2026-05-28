# ZISCS_WO_LOG
**Description:** Write Off error log
**Total Fields:** 4
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs0859`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 |  | Date of entry |
| 4 | `STATUS` | CHAR | 1 |  | Write Off Sttaus |

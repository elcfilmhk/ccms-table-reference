# ZISMDMTRCHANNEL
**Description:** Meter & Register Channels Synchronized to MDMS from CCMS
**Total Fields:** 15
**Key Fields:** MANDT, SERNR, CHANNEL_NO, REGISTER_NO

## Programs Using This Table
- `zisem0003`
- `zismd0007`
- `zismd0010`
- `zismd0011`
- `zismd0023`
- `zismd0024`
- `zismd0025`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `CHANNEL_NO` | NUMC | 3 | 🔑 | Register |
| 4 | `REGISTER_NO` | NUMC | 3 | 🔑 | Register |
| 5 | `CHANNEL_TYPE` | CHAR | 1 |  | Channel type - Interval / Register |
| 6 | `EFF_START_DATE` | DATS | 8 |  | Effective Start Date |
| 7 | `EFF_END_DATE` | DATS | 8 |  | Effective End Date |
| 8 | `CHANNEL_SOURCE` | CHAR | 1 |  | Channel Source |
| 9 | `ANLAGE` | CHAR | 10 |  | Installation |
| 10 | `SP_CHANNEL_NO` | NUMC | 10 |  | Service Point Channel Number |
| 11 | `SP_EFF_START_DAT` | DATS | 8 |  | Service Point Channel Effective Start Date |
| 12 | `SP_EFF_END_DATE` | DATS | 8 |  | Service Point Channel Effective End Date |
| 13 | `REC_DEVICEID` | CHAR | 18 |  | Recording Device ID |
| 14 | `RD_EFF_START_DAT` | DATS | 8 |  | Recording Device Effective Start Date |
| 15 | `RD_EFF_END_DATE` | DATS | 8 |  | Recording Device Effective End Date |

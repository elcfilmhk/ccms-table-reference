# ZISMDACSPCHANNEL
**Description:** Account SP Channel Synchronized to MDMS from CCMS
**Total Fields:** 7
**Key Fields:** MANDT, ACC_LINK_ID, CHANNEL_NO

## Programs Using This Table
- `zismd0007`
- `zismd0010`
- `zismd0011`
- `zismd0025`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACC_LINK_ID` | CHAR | 10 | 🔑 | Installation |
| 3 | `CHANNEL_NO` | NUMC | 6 | 🔑 | Account Service Point Channel Number |
| 4 | `EFF_START_DATE` | DATS | 8 |  | Effective Start Date |
| 5 | `EFF_END_DATE` | DATS | 8 |  | Effective End Date |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `SP_CHANNEL_NO` | NUMC | 10 |  | Service Point Channel Number |

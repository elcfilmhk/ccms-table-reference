# ZISMDSPCHANNEL
**Description:** Service Point Channel Synchronized to MDMS from CCMS
**Total Fields:** 8
**Key Fields:** MANDT, ANLAGE, CHANNEL_NO

## Programs Using This Table
- `zismd0007`
- `zismd0011`
- `zismd0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `CHANNEL_NO` | NUMC | 10 | 🔑 | Service Point Channel Number |
| 4 | `EFF_START_DATE` | DATS | 8 |  | Service Point Link effective start date |
| 5 | `EFF_END_DATE` | DATS | 8 |  | Service Point Link effective end date |
| 6 | `CHANNEL_SOURCE` | CHAR | 1 |  | Channel Source |
| 7 | `CHANNEL_TYPE` | CHAR | 10 |  | Channel type - Interval / Register |
| 8 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |

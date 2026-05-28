# ZISMDOUTSPCNLSET
**Description:** Service Point Channel Set output file
**Total Fields:** 11
**Key Fields:** MANDT, ANLAGE, CHANNELSETID

## Programs Using This Table
- `zismd0007`
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `CHANNELSETID` | CHAR | 34 | 🔑 | The ID of the Service Point Channel Set |
| 4 | `INT_SP_CHANNEL` | NUMC | 10 |  | Service Point Channel Number |
| 5 | `REG_SP_CHANNEL` | NUMC | 10 |  | Service Point Channel Number |
| 6 | `INT_EFF_START` | DATS | 8 |  | Interval Channel Effective Start Date |
| 7 | `REG_EFF_START` | DATS | 8 |  | Register Channel Effective Start Date |
| 8 | `CHANNELSETNAME` | CHAR | 16 |  | Name of the service point channel set |
| 9 | `CHANNELSETTYPE` | CHAR | 16 |  | Channel set type of the service point channel set |
| 10 | `CHANNELSETDESC` | CHAR | 100 |  | Description of the service point channel set |
| 11 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |

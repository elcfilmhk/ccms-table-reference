# ZISMDRDGSET
**Description:** Mapping between the interval channel and the non-CCMS channe
**Total Fields:** 7
**Key Fields:** MANDT, CHANNELSETID

## Programs Using This Table
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHANNELSETID` | CHAR | 16 | 🔑 | The ID of the Service Point Channel Set |
| 3 | `CHANNELSETNAME` | CHAR | 16 |  | The name of the service point channel set |
| 4 | `CHANNELSETDESC` | CHAR | 100 |  | The Description of the service point channel set |
| 5 | `CHANNELSETTYPE` | CHAR | 16 |  | The channel set type of the service point channel set |
| 6 | `INTERVAL_CHANNEL` | NUMC | 5 |  | Service Point Channel |
| 7 | `REGISTER_CHANNEL` | NUMC | 5 |  | Service Point Channel |

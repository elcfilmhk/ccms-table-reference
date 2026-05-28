# ZISEMTIMERANGE
**Description:** Energy Manager - Define on/off peak for ToU type
**Total Fields:** 6
**Key Fields:** MANDT, RTPCOMP, RTPCOMPCODE, TOUPERIOD

## Programs Using This Table
- `zisem_general_settings`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RTPCOMP` | CHAR | 10 | 🔑 | RTP component |
| 3 | `RTPCOMPCODE` | NUMC | 3 | 🔑 | Internal code for individual levels of RTP component |
| 4 | `TOUPERIOD` | CHAR | 10 | 🔑 | Time-of-use type |
| 5 | `TOUPERTEXT` | CHAR | 40 |  | Description of time-of-use type |
| 6 | `ONOFF` | CHAR | 1 |  | Energy Manager - Flag for On/Off peak |

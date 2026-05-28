# ZISMDOUTINTCHANL
**Description:** Interval Channel Output File
**Total Fields:** 19
**Key Fields:** MANDT, METERLINK_ID, CHANNEL_NO

## Programs Using This Table
- `zismd0007`
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METERLINK_ID` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `CHANNEL_NO` | NUMC | 3 | 🔑 | Register |
| 4 | `REGISTER_NO` | NUMC | 3 |  | Register |
| 5 | `ML_EFF_START_DAT` | DATS | 8 |  | Effective start date for the register linked to the meter |
| 6 | `EFF_START_DATE` | DATS | 8 |  | Effective start date of the register |
| 7 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 8 | `ROLL_INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 9 | `PULSE_MISC_MULTI` | NUMC | 4 |  | Pulse Misc Multiplier of the interval channel |
| 10 | `PULSE_OFFSET` | NUMC | 4 |  | Pulse offset of the interval channel |
| 11 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 12 | `KEMULTIPLIER` | NUMC | 4 |  | KE Multiplier of the interval channel |
| 13 | `ANLAGE` | CHAR | 10 |  | Installation |
| 14 | `SP_CHANNEL_NO` | NUMC | 10 |  | Service Point Channel Number |
| 15 | `SP_EFF_START_DAT` | DATS | 8 |  | Service Point Link effective start date |
| 16 | `REC_DEVICEID` | CHAR | 18 |  | Recording Device ID |
| 17 | `RD_EFF_START_DAT` | DATS | 8 |  | Recording Device effective start date |
| 18 | `CHANNEL_SOURCE` | CHAR | 1 |  | Channel Source |
| 19 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |

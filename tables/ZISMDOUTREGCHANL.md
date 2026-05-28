# ZISMDOUTREGCHANL
**Description:** Register Channel Output File
**Total Fields:** 26
**Key Fields:** MANDT, METERLINK_ID, ZWNUMMER

## Programs Using This Table
- `zismd0007`
- `zismd0008`
- `zismd0010`
- `zismd0011`
- `zismd0024`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METERLINK_ID` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `ML_EFF_START_DAT` | DATS | 8 |  | Effective start date for the register linked to the meter |
| 5 | `EFF_START_DATE` | DATS | 8 |  | Effective start date of the register |
| 6 | `DISPLAY_CODE` | CHAR | 2 |  | Register Display Code |
| 7 | `STANZVORNAC` | NUMC | 2 |  | Total number of dial of the register |
| 8 | `STANZNAC` | NUMC | 2 |  | Places after the decimal in a register |
| 9 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 10 | `DESCRIPTION` | CHAR | 100 |  | Description of the register |
| 11 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 12 | `SEQUENCE` | NUMC | 4 |  | Sequence of meter in the route |
| 13 | `READ_TYPE_CODE` | CHAR | 16 |  | Read type code |
| 14 | `DISP_MULTIPLIER` | NUMC | 4 |  | Last Test Date of the meter |
| 15 | `REGDEC_NAMETYPE` | CHAR | 50 |  | Register Decode Name Type of register |
| 16 | `ZWFAKT` | DEC | 12 |  | Register factor |
| 17 | `ANLAGE` | CHAR | 10 |  | Installation |
| 18 | `SP_CHANNEL_NO` | NUMC | 10 |  | Service Point Channel Number |
| 19 | `SP_EFF_START_DAT` | DATS | 8 |  | Service Point Link effective start date |
| 20 | `REC_DEVICEID` | CHAR | 18 |  | Recording Device ID |
| 21 | `RD_EFF_START_DAT` | DATS | 8 |  | Recording Device effective start date |
| 22 | `ZWTYP` | NUMC | 2 |  | Register category |
| 23 | `ZWART` | CHAR | 2 |  | Register type |
| 24 | `BLIWIRK` | NUMC | 2 |  | Reactive, apparent, or active registers |
| 25 | `CHANNEL_SOURCE` | CHAR | 1 |  | Channel Source |
| 26 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |

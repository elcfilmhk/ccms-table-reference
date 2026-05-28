# ZISMDCONVRECD
**Description:** RecordingDevice Output Interface File Rec from Parallel Proc
**Total Fields:** 17
**Key Fields:** MANDT, REC_DEVICEID

## Programs Using This Table
- `zismd0005`
- `zismd0006`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REC_DEVICEID` | CHAR | 18 | 🔑 | Recording Device ID |
| 3 | `DEVICEID` | CHAR | 50 |  | The COMM Device ID of the recording device |
| 4 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 5 | `HERST` | CHAR | 30 |  | Manufacturer of asset |
| 6 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 7 | `DEVICE_TYPE` | CHAR | 16 |  | Recording Device Type of the recording Device |
| 8 | `DECODE_TYPE_CODE` | CHAR | 16 |  | Recording Device Type code of the recording device |
| 9 | `TZONE` | CHAR | 30 |  | The time zone of the recording device |
| 10 | `EXT_SYSTEM_ID` | CHAR | 16 |  | The external system id of the recording device |
| 11 | `EXT_REC_DEVICEID` | CHAR | 18 |  | Serial Number |
| 12 | `EFF_START_DATE` | DATS | 8 |  | Effective Start Date |
| 13 | `BATTERY_DAY` | NUMC | 5 |  | The number of days on battery |
| 14 | `BATTERY_MINUTE` | NUMC | 5 |  | The number of minutes on battery |
| 15 | `BATTERY_INSTDATE` | DATS | 8 |  | Install date of the battery |
| 16 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |
| 17 | `ANLAGE` | CHAR | 10 |  | Installation |

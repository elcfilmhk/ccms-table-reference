# ZISDMREPGM
**Description:** Custom table for re-program rate ID
**Total Fields:** 19
**Key Fields:** MANDT, ZZRATEID

## Programs Using This Table
- `zisdh0004`
- `zisdm0010`
- `zisdm0016`
- `zisdm0037`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`
- `zisdm0108`
- `zisdm0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZRATEID` | CHAR | 8 | 🔑 | The ID of the re-program rate |
| 3 | `ZZEFFSTARTDATE` | DATS | 8 |  | The start effective date of the re-program rate |
| 4 | `ZZEFFENDDATE` | DATS | 8 |  | The end effective date of the re-program rate |
| 5 | `ZZDESCRIPTION` | CHAR | 80 |  | Description of the re-program rate |
| 6 | `ZZLASTTESTDATE` | DATS | 8 |  | The last test date after which the device will be re-program |
| 7 | `ZZSTRTDLDATE` | DATS | 8 |  | The starting date on and after the download to ITRON |
| 8 | `ZZSTATUS` | CHAR | 1 |  | Status of the re-program rate |
| 9 | `ZZCHGHOLIDAY` | CHAR | 1 |  | Indicator for re-program rate for changing holiday only |
| 10 | `ZZMANUFACTURER` | CHAR | 40 |  | Manufacturer of PPM |
| 11 | `ZZMODEL` | CHAR | 40 |  | Model of PPM |
| 12 | `ZZNEWRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 13 | `ZZNEWRATESTATUS` | CHAR | 1 |  | Status of the new rate ID |
| 14 | `ZZCREUSERID` | CHAR | 12 |  | User ID who created the re-program rate |
| 15 | `ZZCREDATE` | DATS | 8 |  | Creation date of the re-program rate |
| 16 | `ZZCRETIME` | TIMS | 6 |  | Creation time of the re-program rate |
| 17 | `ZZLAUSERID` | CHAR | 12 |  | Last update user ID |
| 18 | `ZZLADATE` | DATS | 8 |  | Last update date |
| 19 | `ZZLATIME` | TIMS | 6 |  | Last update time |

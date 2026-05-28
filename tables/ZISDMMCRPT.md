# ZISDMMCRPT
**Description:** Master Check Installation Report Table
**Total Fields:** 14
**Key Fields:** MANDT, ZZMCMANLAGE, ZZANLAGE, ZZMONTH, ZZYEAR

## Programs Using This Table
- `zisdm0084`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZMCMANLAGE` | CHAR | 10 | 🔑 | The ID of the Master Check Installation |
| 3 | `ZZANLAGE` | CHAR | 10 | 🔑 | Installation under MCM monitoring |
| 4 | `ZZMONTH` | NUMC | 2 | 🔑 | Consumption Month |
| 5 | `ZZYEAR` | NUMC | 4 | 🔑 | Year for period |
| 6 | `ZZNOOFMCM` | NUMC | 5 |  | Total number of Master Check Meters at Master Installation |
| 7 | `ZZVOLTAGE` | NUMC | 7 |  | Voltage |
| 8 | `ZZTOTKWHMCM` | NUMC | 10 |  | Total kWh consumption of Master Check Installation |
| 9 | `ZZNOOFSUBMETERS` | NUMC | 5 |  | Total number of Meters at Sub-Installation |
| 10 | `ZZTOTALKWH` | NUMC | 10 |  | Consumption (kWh) of installation under MCM |
| 11 | `ZZVAR` | DEC | 13 |  | Variance MCM consumpt. and consumpt. of  inst. in percentage |
| 12 | `ZZVARUNIT` | DEC | 13 |  | Variance MCM consumpt. and consumpt. of inst. in value |
| 13 | `ZZINSTSTATUS` | CHAR | 1 |  | Installation(s) status |
| 14 | `ZZREMARKS` | CHAR | 40 |  | Free-text remark to insert notes and additional information |

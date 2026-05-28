# ZISDMBINST
**Description:** Customized structure for bulk installation
**Total Fields:** 32
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0022`
- `zisdm0022_bulk`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZSELCOL` | CHAR | 1 |  | Selected Line |
| 2 | `ZZREFNO` | CHAR | 3 |  | Reference number |
| 3 | `RE_SYS_LOC` | CHAR | 10 |  | RE System Location |
| 4 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 5 | `RE_SYS_NAM_CH` | CHAR | 100 |  | Description |
| 6 | `RE_SOURCE` | CHAR | 2 |  | RE Source |
| 7 | `RE_SOURCE_D` | CHAR | 30 |  | Description |
| 8 | `RE_SOURCE_FIT_RATE` | CHAR | 2 |  | RE Source |
| 9 | `RE_SOURCE_FIT_RATE_D` | CHAR | 30 |  | Description |
| 10 | `TOT_GEN_CAP` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 11 | `FIT_RATE` | DEC | 4 |  | FiT Rate |
| 12 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 13 | `METER_TYPE_D` | CHAR | 30 |  | Description |
| 14 | `MET_LOC_DESC` | CHAR | 50 |  | Meter Location Description |
| 15 | `MET_DOC_LINK` | CHAR | 250 |  | Meter Document link |
| 16 | `CORRECTION` | CHAR | 1 |  | Activate Tips |
| 17 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 18 | `ZZPREMISEADDR` | CHAR | 60 |  | Premise address |
| 19 | `ZZDEVICE` | CHAR | 18 |  | Serial Number |
| 20 | `ZZMETERSIZE` | CHAR | 18 |  | Size/dimension |
| 21 | `ZZMETERROLE` | CHAR | 30 |  | Meter Role |
| 22 | `ZZSUBMETER` | CHAR | 1 |  | Checkbox for sub-meter |
| 23 | `ZZMASTERINST` | CHAR | 10 |  | Installation |
| 24 | `ZZACTDATE` | DATS | 8 |  | Activity date |
| 25 | `ZZDEVLOC` | CHAR | 30 |  | Device Location |
| 26 | `ZZPRCONSUMPTION` | CHAR | 14 |  | Periodic Consumption |
| 27 | `ZZDAYS` | NUMC | 3 |  | Number of days |
| 28 | `ZZRATETYPE` | CHAR | 8 |  | Rate Type |
| 29 | `ZZFACTGROUP` | CHAR | 10 |  | Rate fact group |
| 30 | `ZZREMARK` | CHAR | 100 |  | Message line |
| 31 | `COMM_START_DATE` | DATS | 8 |  | Commissioning Start Date |
| 32 | `COMM_END_DATE` | DATS | 8 |  | Commissioning End Date |

# ZISDMEABLU
**Description:** BAPIEABLU for Locked Records
**Total Fields:** 24
**Key Fields:** MANDT, MATERIAL, SERIALNO, REGISTER, MRREASON, MRIDNUMBER

## Programs Using This Table
- `zisdm0040`
- `zisdm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MATERIAL` | CHAR | 18 | 🔑 | Material Number |
| 3 | `SERIALNO` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `REGISTER` | NUMC | 3 | 🔑 | Register |
| 5 | `MRREASON` | CHAR | 2 | 🔑 | Meter reading reason |
| 6 | `MRIDNUMBER` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 7 | `READINGRESULT` | CHAR | 32 |  | Meter reading recorded |
| 8 | `METERREADINGNOTE` | CHAR | 4 |  | Note from meter reader |
| 9 | `ACTUALCUSTMRTYPE` | CHAR | 2 |  | Meter reading type |
| 10 | `METERREADER` | CHAR | 3 |  | Meter reader number |
| 11 | `MRDATEFORBILLING` | DATS | 8 |  | Meter reading date relevant to billing |
| 12 | `MRTIMEFORBILLING` | CHAR | 4 |  | Meter reading time (relevant to billing) |
| 13 | `ACTUALMRDATE` | DATS | 8 |  | Actual meter reading date |
| 14 | `ACTUALMRTIME` | CHAR | 4 |  | Actual meter reading time |
| 15 | `MRDATEOFMAXIMUM` | DATS | 8 |  | Date of maximum meter reading |
| 16 | `MRTIMEOFMAXIMUM` | CHAR | 4 |  | Time of maximum meter reading |
| 17 | `SMORDER` | CHAR | 12 |  | Service order or service notification number |
| 18 | `ACTIVE` | CHAR | 1 |  | Meter reading active |
| 19 | `REFNUMBER` | CHAR | 15 |  | Code for Identifying a Register |
| 20 | `TARGETMRDATE` | DATS | 8 |  | Planned Meter Reading Date (for Upload) |
| 21 | `EXT_UI` | CHAR | 50 |  | Point of delivery ID |
| 22 | `PROCESSED` | CHAR | 1 |  | Processing Complete |
| 23 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 24 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

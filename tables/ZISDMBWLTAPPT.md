# ZISDMBWLTAPPT
**Description:** SRD meeting the appointment slot for BW Reporting
**Total Fields:** 15
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0152`
- `zisdm0245`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `APP_MET_ADATSOLL` | CHAR | 1 |  | Y/N - Sch. MR meter reading date meet / do not meet the appt |
| 8 | `APP_MET_ADAT` | CHAR | 1 |  | Y/N - Act. MR meter reading date meet / do not meet the appt |
| 9 | `SERNR` | CHAR | 18 |  | Serial Number |
| 10 | `MASTER_INST` | CHAR | 10 |  | Installation |
| 11 | `SUB_INST` | CHAR | 10 |  | Installation |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `CTIME` | TIMS | 6 |  | Time changed |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `UTIME` | TIMS | 6 |  | Time changed |

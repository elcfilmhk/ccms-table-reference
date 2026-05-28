# ZISEDINSTPROF
**Description:** Installation and profile table
**Total Fields:** 13
**Key Fields:** MANDT, AUTOKEY

## Programs Using This Table
- `zisdm0285`
- `zised0005`
- `zised0007`
- `zised0023`
- `zised0028`
- `zised0030`
- `zised0041`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUTOKEY` | NUMC | 14 | 🔑 | EDM - Installation Profile Key Number |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 5 | `DATEFROM` | DATS | 8 |  | EDM - Date From |
| 6 | `DATETO` | DATS | 8 |  | EDM - Date To |
| 7 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 8 | `MULTIPLE_FLG` | CHAR | 1 |  | EDM - Multiple Contracts Indicator |
| 9 | `OUTLINE_FLG` | CHAR | 1 |  | EDM - Outline Contract Indicator |
| 10 | `OUTLINE_PROFILE` | NUMC | 18 |  | EDM - Outline Profile |
| 11 | `CHANGE_DT` | DATS | 8 |  | Date of Last Change |
| 12 | `CHANGE_TM` | TIMS | 6 |  | EDM - Time of Last Change |
| 13 | `CHANGE_USER` | CHAR | 12 |  | Name of person who changed object |

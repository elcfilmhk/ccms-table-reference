# ZISEDBWFITPROFFI
**Description:** EDM - Export table
**Total Fields:** 109
**Key Fields:** MANDT, SNAPSHOT_DATE, PROFILE, SERNR, ZWNUMMER, KENNZIFF, METER_TYPE, PROFVALDAY

## Programs Using This Table
- `zised0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SNAPSHOT_DATE` | DATS | 8 | 🔑 | Date (Snapshot) |
| 3 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 6 | `KENNZIFF` | CHAR | 15 | 🔑 | Code for Identifying a Register |
| 7 | `METER_TYPE` | CHAR | 1 | 🔑 | Meter Type |
| 8 | `PROFVALDAY` | DATS | 8 | 🔑 | Profile date, normally Snapshot date - 1 |
| 9 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 10 | `MASSBILL` | UNIT | 3 |  | Unit of measurement for meter reading |
| 11 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 12 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 13 | `VAL0000` | DEC | 31 |  | Profile value at application level |
| 14 | `VAL0030` | DEC | 31 |  | Profile value at application level |
| 15 | `VAL0100` | DEC | 31 |  | Profile value at application level |
| 16 | `VAL0130` | DEC | 31 |  | Profile value at application level |
| 17 | `VAL0200` | DEC | 31 |  | Profile value at application level |
| 18 | `VAL0230` | DEC | 31 |  | Profile value at application level |
| 19 | `VAL0300` | DEC | 31 |  | Profile value at application level |
| 20 | `VAL0330` | DEC | 31 |  | Profile value at application level |
| 21 | `VAL0400` | DEC | 31 |  | Profile value at application level |
| 22 | `VAL0430` | DEC | 31 |  | Profile value at application level |
| 23 | `VAL0500` | DEC | 31 |  | Profile value at application level |
| 24 | `VAL0530` | DEC | 31 |  | Profile value at application level |
| 25 | `VAL0600` | DEC | 31 |  | Profile value at application level |
| 26 | `VAL0630` | DEC | 31 |  | Profile value at application level |
| 27 | `VAL0700` | DEC | 31 |  | Profile value at application level |
| 28 | `VAL0730` | DEC | 31 |  | Profile value at application level |
| 29 | `VAL0800` | DEC | 31 |  | Profile value at application level |
| 30 | `VAL0830` | DEC | 31 |  | Profile value at application level |
| 31 | `VAL0900` | DEC | 31 |  | Profile value at application level |
| 32 | `VAL0930` | DEC | 31 |  | Profile value at application level |
| 33 | `VAL1000` | DEC | 31 |  | Profile value at application level |
| 34 | `VAL1030` | DEC | 31 |  | Profile value at application level |
| 35 | `VAL1100` | DEC | 31 |  | Profile value at application level |
| 36 | `VAL1130` | DEC | 31 |  | Profile value at application level |
| 37 | `VAL1200` | DEC | 31 |  | Profile value at application level |
| 38 | `VAL1230` | DEC | 31 |  | Profile value at application level |
| 39 | `VAL1300` | DEC | 31 |  | Profile value at application level |
| 40 | `VAL1330` | DEC | 31 |  | Profile value at application level |
| 41 | `VAL1400` | DEC | 31 |  | Profile value at application level |
| 42 | `VAL1430` | DEC | 31 |  | Profile value at application level |
| 43 | `VAL1500` | DEC | 31 |  | Profile value at application level |
| 44 | `VAL1530` | DEC | 31 |  | Profile value at application level |
| 45 | `VAL1600` | DEC | 31 |  | Profile value at application level |
| 46 | `VAL1630` | DEC | 31 |  | Profile value at application level |
| 47 | `VAL1700` | DEC | 31 |  | Profile value at application level |
| 48 | `VAL1730` | DEC | 31 |  | Profile value at application level |
| 49 | `VAL1800` | DEC | 31 |  | Profile value at application level |
| 50 | `VAL1830` | DEC | 31 |  | Profile value at application level |
| 51 | `VAL1900` | DEC | 31 |  | Profile value at application level |
| 52 | `VAL1930` | DEC | 31 |  | Profile value at application level |
| 53 | `VAL2000` | DEC | 31 |  | Profile value at application level |
| 54 | `VAL2030` | DEC | 31 |  | Profile value at application level |
| 55 | `VAL2100` | DEC | 31 |  | Profile value at application level |
| 56 | `VAL2130` | DEC | 31 |  | Profile value at application level |
| 57 | `VAL2200` | DEC | 31 |  | Profile value at application level |
| 58 | `VAL2230` | DEC | 31 |  | Profile value at application level |
| 59 | `VAL2300` | DEC | 31 |  | Profile value at application level |
| 60 | `VAL2330` | DEC | 31 |  | Profile value at application level |
| 61 | `STATVAL0000` | CHAR | 4 |  | Status of profile value in interface |
| 62 | `STATVAL0030` | CHAR | 4 |  | Status of profile value in interface |
| 63 | `STATVAL0100` | CHAR | 4 |  | Status of profile value in interface |
| 64 | `STATVAL0130` | CHAR | 4 |  | Status of profile value in interface |
| 65 | `STATVAL0200` | CHAR | 4 |  | Status of profile value in interface |
| 66 | `STATVAL0230` | CHAR | 4 |  | Status of profile value in interface |
| 67 | `STATVAL0300` | CHAR | 4 |  | Status of profile value in interface |
| 68 | `STATVAL0330` | CHAR | 4 |  | Status of profile value in interface |
| 69 | `STATVAL0400` | CHAR | 4 |  | Status of profile value in interface |
| 70 | `STATVAL0430` | CHAR | 4 |  | Status of profile value in interface |
| 71 | `STATVAL0500` | CHAR | 4 |  | Status of profile value in interface |
| 72 | `STATVAL0530` | CHAR | 4 |  | Status of profile value in interface |
| 73 | `STATVAL0600` | CHAR | 4 |  | Status of profile value in interface |
| 74 | `STATVAL0630` | CHAR | 4 |  | Status of profile value in interface |
| 75 | `STATVAL0700` | CHAR | 4 |  | Status of profile value in interface |
| 76 | `STATVAL0730` | CHAR | 4 |  | Status of profile value in interface |
| 77 | `STATVAL0800` | CHAR | 4 |  | Status of profile value in interface |
| 78 | `STATVAL0830` | CHAR | 4 |  | Status of profile value in interface |
| 79 | `STATVAL0900` | CHAR | 4 |  | Status of profile value in interface |
| 80 | `STATVAL0930` | CHAR | 4 |  | Status of profile value in interface |
| 81 | `STATVAL1000` | CHAR | 4 |  | Status of profile value in interface |
| 82 | `STATVAL1030` | CHAR | 4 |  | Status of profile value in interface |
| 83 | `STATVAL1100` | CHAR | 4 |  | Status of profile value in interface |
| 84 | `STATVAL1130` | CHAR | 4 |  | Status of profile value in interface |
| 85 | `STATVAL1200` | CHAR | 4 |  | Status of profile value in interface |
| 86 | `STATVAL1230` | CHAR | 4 |  | Status of profile value in interface |
| 87 | `STATVAL1300` | CHAR | 4 |  | Status of profile value in interface |
| 88 | `STATVAL1330` | CHAR | 4 |  | Status of profile value in interface |
| 89 | `STATVAL1400` | CHAR | 4 |  | Status of profile value in interface |
| 90 | `STATVAL1430` | CHAR | 4 |  | Status of profile value in interface |
| 91 | `STATVAL1500` | CHAR | 4 |  | Status of profile value in interface |
| 92 | `STATVAL1530` | CHAR | 4 |  | Status of profile value in interface |
| 93 | `STATVAL1600` | CHAR | 4 |  | Status of profile value in interface |
| 94 | `STATVAL1630` | CHAR | 4 |  | Status of profile value in interface |
| 95 | `STATVAL1700` | CHAR | 4 |  | Status of profile value in interface |
| 96 | `STATVAL1730` | CHAR | 4 |  | Status of profile value in interface |
| 97 | `STATVAL1800` | CHAR | 4 |  | Status of profile value in interface |
| 98 | `STATVAL1830` | CHAR | 4 |  | Status of profile value in interface |
| 99 | `STATVAL1900` | CHAR | 4 |  | Status of profile value in interface |
| 100 | `STATVAL1930` | CHAR | 4 |  | Status of profile value in interface |
| 101 | `STATVAL2000` | CHAR | 4 |  | Status of profile value in interface |
| 102 | `STATVAL2030` | CHAR | 4 |  | Status of profile value in interface |
| 103 | `STATVAL2100` | CHAR | 4 |  | Status of profile value in interface |
| 104 | `STATVAL2130` | CHAR | 4 |  | Status of profile value in interface |
| 105 | `STATVAL2200` | CHAR | 4 |  | Status of profile value in interface |
| 106 | `STATVAL2230` | CHAR | 4 |  | Status of profile value in interface |
| 107 | `STATVAL2300` | CHAR | 4 |  | Status of profile value in interface |
| 108 | `STATVAL2330` | CHAR | 4 |  | Status of profile value in interface |
| 109 | `SNAPSHOT_TIME` | TIMS | 6 |  | Time (Snapshot) |

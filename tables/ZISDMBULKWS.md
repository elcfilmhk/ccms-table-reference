# ZISDMBULKWS
**Description:** Customized table for worksheet data
**Total Fields:** 21
**Key Fields:** MANDT, ZZWORKSHEETNUM, ZZREFNO

## Programs Using This Table
- `zisdm0022`
- `zisdm0022_bulk`
- `zisdm0022_mail`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZWORKSHEETNUM` | NUMC | 9 | 🔑 | Worksheet Number |
| 3 | `ZZREFNO` | CHAR | 3 | 🔑 | Reference number |
| 4 | `ZZPREMISEADDR` | CHAR | 60 |  | Premise address |
| 5 | `ZZREGIONGRP` | CHAR | 8 |  | Regional structure grouping |
| 6 | `ZZCONNOBJ` | CHAR | 30 |  | Functional Location |
| 7 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 8 | `ZZOLDDEVICE` | CHAR | 18 |  | Serial Number |
| 9 | `ZZOLDMETERSIZE` | CHAR | 18 |  | Size/dimension |
| 10 | `ZZINSTDATE` | DATS | 8 |  | Installation date |
| 11 | `ZZLASTREADING` | CHAR | 36 |  | Expected meter reading in screen format |
| 12 | `ZZNEWDEVICE` | CHAR | 18 |  | Serial Number |
| 13 | `ZZNEWMETERSIZE` | CHAR | 18 |  | Size/dimension |
| 14 | `ZZREPLDATE` | DATS | 8 |  | Replacement date |
| 15 | `ZZCREATEDBY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `ZZSELCOL` | CHAR | 1 |  | Selected line |
| 17 | `ZZOLDEQUNR` | CHAR | 18 |  | Equipment Number |
| 18 | `ZZNEWEQUNR` | CHAR | 18 |  | Equipment Number |
| 19 | `ZZREMARK` | CHAR | 100 |  | Message line |
| 20 | `ZZLOST` | CHAR | 1 |  | Lost |
| 21 | `ZZTEST` | CHAR | 1 |  | Test |

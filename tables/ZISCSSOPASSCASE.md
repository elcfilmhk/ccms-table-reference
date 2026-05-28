# ZISCSSOPASSCASE
**Description:** Passed Case in Service Notification
**Total Fields:** 22
**Key Fields:** MANDT, QMNUM, SEQ

## Programs Using This Table
- `ziscs0009`
- `ziscs0015`
- `ziscs0468`
- `ziscsriaufk20`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QMNUM` | CHAR | 12 | 🔑 | Notification No |
| 3 | `SEQ` | NUMC | 4 | 🔑 | Sequence Number |
| 4 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `DESIGNELECTWKID` | CHAR | 20 |  | Design Elect Wk ID |
| 9 | `DESIGNCONTRACTORID` | CHAR | 20 |  | Design Contractor ID |
| 10 | `INSTALLATIONELECTWKID` | CHAR | 20 |  | Installation Elect Wk ID |
| 11 | `INSTALLATIONCONTRACTORID` | CHAR | 20 |  | Installation Elect Contractor ID |
| 12 | `PROTECTTYPE` | CHAR | 20 |  | Protect Type |
| 13 | `CABLESIZE1` | CHAR | 20 |  | Cable Size 1 |
| 14 | `CABLESIZE2` | CHAR | 20 |  | Cable Size 2 in unit mm |
| 15 | `MAINSWITCH` | CHAR | 30 |  | Main Switch in unit A |
| 16 | `INSULATIONR` | CHAR | 20 |  | Insulation Resistance in unit MOhms |
| 17 | `BREAKINGCAPACITY` | CHAR | 10 |  | Breaking Capacity in unit kA |
| 18 | `PDAEARTHLOOPIMP` | CHAR | 5 |  | Earth Loop Imp in unit Ohms |
| 19 | `JOBCURRENT` | CHAR | 20 |  | Live Loop Imp in unit Ohms |
| 20 | `KVARINSTALLED` | CHAR | 4 |  | Max Fault Current in unit kA |
| 21 | `EOEXEMPTED` | CHAR | 1 |  | Exemption |
| 22 | `GOVERNMENTWORK` | CHAR | 1 |  | Government Installation |

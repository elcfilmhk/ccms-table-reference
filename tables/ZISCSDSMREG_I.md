# ZISCSDSMREG_I
**Description:** Item table for DSM registration
**Total Fields:** 18
**Key Fields:** MANDT, VKONT, ITEMNUMBER, DSMPROGID

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zisbi0234`
- `ziscs0480`
- `ziscs0485`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ITEMNUMBER` | CHAR | 3 | 🔑 | Item Number |
| 4 | `DSMPROGID` | CHAR | 6 | 🔑 | DSM Program ID |
| 5 | `REGDATE` | DATS | 8 |  | Registration Date |
| 6 | `CURRDSMGRP` | CHAR | 8 |  | Current DSM Group for CA |
| 7 | `ACTIVITY` | CHAR | 5 |  | Activity |
| 8 | `DSMOPTFLG` | CHAR | 1 |  | Flag when Activity is OPTOT as part of end of program |
| 9 | `EFFEDATCOD` | CHAR | 2 |  | Effective Date Code |
| 10 | `EFFECDATE` | DATS | 8 |  | Effective Date of Change |
| 11 | `PROCSSTATUS` | CHAR | 2 |  | Processing status |
| 12 | `REQSRCCODE` | CHAR | 2 |  | Requesting Source Code |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `ERZET` | TIMS | 6 |  | Entry time |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 17 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 18 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

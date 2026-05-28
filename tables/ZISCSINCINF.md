# ZISCSINCINF
**Description:** TCOM Customer Query Output Row Structure
**Total Fields:** 42
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0116`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PREMISENO` | CHAR | 10 |  | &nbsp; |
| 2 | `TIMEINDICATOR` | CHAR | 1 |  | &nbsp; |
| 3 | `DEENERGID` | CHAR | 11 |  | &nbsp; |
| 4 | `DEENERGSTATUS` | CHAR | 40 |  | &nbsp; |
| 5 | `ORDERID` | CHAR | 24 |  | &nbsp; |
| 6 | `ORDERSTATUS` | CHAR | 16 |  | &nbsp; |
| 7 | `INCIDENTID` | CHAR | 11 |  | &nbsp; |
| 8 | `PROJECTID` | CHAR | 11 |  | &nbsp; |
| 9 | `CUSTMSG` | CHAR | 255 |  | &nbsp; |
| 10 | `ORDERLOC` | CHAR | 80 |  | &nbsp; |
| 11 | `DEENERGTYPE` | CHAR | 20 |  | &nbsp; |
| 12 | `CRITICALFLAG` | CHAR | 1 |  | &nbsp; |
| 13 | `PLANREASON1` | CHAR | 100 |  | &nbsp; |
| 14 | `OPCENTRE` | CHAR | 2 |  | &nbsp; |
| 15 | `REGION` | CHAR | 10 |  | &nbsp; |
| 16 | `MAINCREW` | CHAR | 32 |  | &nbsp; |
| 17 | `LEADCREWMEMBER` | CHAR | 24 |  | &nbsp; |
| 18 | `CREWCONTACT` | CHAR | 100 |  | &nbsp; |
| 19 | `PLANOUTAGEFROM` | CHAR | 20 |  | &nbsp; |
| 20 | `PLANOUTAGETO` | CHAR | 20 |  | &nbsp; |
| 21 | `DEENERGSTART` | CHAR | 20 |  | &nbsp; |
| 22 | `OESTRESTORETIME` | CHAR | 20 |  | &nbsp; |
| 23 | `ESTRESTORETIME` | CHAR | 20 |  | &nbsp; |
| 24 | `FIRSTDISPATCHTIME` | CHAR | 20 |  | &nbsp; |
| 25 | `FIRSTARRIVALTIME` | CHAR | 20 |  | &nbsp; |
| 26 | `APPOINTMENTIME` | CHAR | 20 |  | &nbsp; |
| 27 | `DEENERGRESTORESTATUS` | CHAR | 60 |  | &nbsp; |
| 28 | `DEENERGRESTORETIME` | CHAR | 20 |  | &nbsp; |
| 29 | `DEENERGNOCUSTAFFECTED` | NUMC | 10 |  | &nbsp; |
| 30 | `FULLRESTORETIME` | CHAR | 20 |  | &nbsp; |
| 31 | `MAXNOCUSTAFFECTED` | NUMC | 10 |  | &nbsp; |
| 32 | `VOLTLEVEL` | CHAR | 10 |  | &nbsp; |
| 33 | `KVALOSS` | NUMC | 10 |  | &nbsp; |
| 34 | `CAUSE` | CHAR | 32 |  | &nbsp; |
| 35 | `ORDERCOMMENT` | CHAR | 200 |  | &nbsp; |
| 36 | `INCIDENTSTARTTIME` | CHAR | 20 |  | &nbsp; |
| 37 | `INCIDENTSTATUS` | CHAR | 32 |  | &nbsp; |
| 38 | `AFFECTEDAREA` | CHAR | 80 |  | &nbsp; |
| 39 | `ORDERFDCOMPLETETIME` | CHAR | 20 |  | &nbsp; |
| 40 | `ZZESTRESDATE` | DATS | 8 |  | Date |
| 41 | `ZZESTRESTIME` | TIMS | 6 |  | Time |
| 42 | `ZZGROUP` | NUMC | 3 |  | &nbsp; |

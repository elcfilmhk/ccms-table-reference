# ZISDMADREVENT
**Description:** ADR Event Information Header
**Total Fields:** 21
**Key Fields:** MANDT, EVENTNAME, BATCHID

## Programs Using This Table
- `ziscs0528`
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisdm0327_adr`
- `zisdm0328_adr`
- `zisdm0355`
- `zisdm0356`
- `zisdm0357`
- `zisdm0357_backup`
- `zisdm0359`
- `zisfi0249_dnld`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0274`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `BATCHID` | CHAR | 80 | 🔑 | Batch ID |
| 4 | `STARTDATE` | DATS | 8 |  | Date |
| 5 | `STARTTIME` | TIMS | 6 |  | Time |
| 6 | `DURATION` | NUMC | 4 |  | Event Duration |
| 7 | `UNIT` | CHAR | 5 |  | Duration Unit |
| 8 | `EVENTSTATUS` | CHAR | 15 |  | ADR Event Execution Status |
| 9 | `EVENTTYPE` | CHAR | 15 |  | ADR Event Notification Types |
| 10 | `EVENTREMARKS` | CHAR | 80 |  | Remarks |
| 11 | `STATUS_CHG_DAT` | DATS | 8 |  | Date |
| 12 | `STATUS_CHG_TIME` | TIMS | 6 |  | Time |
| 13 | `DUMMY_EVENT` | CHAR | 1 |  | Dummy Event Indicator |
| 14 | `APPROVER` | CHAR | 12 |  | User Name |
| 15 | `OPTOT_DEADLINE` | TIMS | 6 |  | Opt-Out Time |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `ERZET` | TIMS | 6 |  | Entry time |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 21 | `AEZET` | TIMS | 6 |  | Time last change was made |

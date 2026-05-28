# ZISDMADRDRCUST
**Description:** ADR DR Customers Infomration by event
**Total Fields:** 19
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, PROGNAME

## Programs Using This Table
- `ziscs0528`
- `ziscs_drevent_del`
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisdm0314_adr`
- `zisdm0327_adr`
- `zisdm0328_adr`
- `zisdm0355`
- `zisdm0356`
- `zisdm0369_candi`
- `zisdm0371`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0251`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `PROGNAME` | CHAR | 50 | 🔑 | Program Name |
| 5 | `DRCUSTNAME` | CHAR | 80 |  | DR Customer name |
| 6 | `PAYEENAME` | CHAR | 80 |  | Payee Name |
| 7 | `ADDRESS` | CHAR | 100 |  | Customer Address |
| 8 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 9 | `CLP_ACC_MGR` | CHAR | 20 |  | CLP Account Manager |
| 10 | `BASELINE` | CHAR | 10 |  | Baseline Method |
| 11 | `PARTICIPATION` | CHAR | 1 |  | Y/N |
| 12 | `CSTATUS` | CHAR | 1 |  | ADR DR Customer Baseline Calculation status |
| 13 | `LOGID` | NUMC | 10 |  | DR Log ID |
| 14 | `OPTOT_DATE` | DATS | 8 |  | OPT Out Date |
| 15 | `OPTOT_TIME` | TIMS | 6 |  | Opt-Out Time |
| 16 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 17 | `CREATION_TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 18 | `CHANGED_ON` | CHAR | 12 |  | Name of person who changed object |
| 19 | `CHANGE_TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |

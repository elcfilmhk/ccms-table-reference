# ZISCS_PROG_TRACK
**Description:** Table to store Progress Tracking info for Work Orders
**Total Fields:** 18
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `zisbi0186`
- `ziscs0005`
- `ziscs0340`
- `ziscs0465`
- `zisuorder`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ZZEXPCOMDAT` | DATS | 8 |  | Anticipated Construction Completion Date |
| 4 | `ZZACTCOMDAT` | DATS | 8 |  | Actual Completion Date |
| 5 | `ZZTARCOMDAT` | DATS | 8 |  | Target Completion Date |
| 6 | `ZZUSERID` | CHAR | 10 |  | Engineer User ID |
| 7 | `ZZSURNAME` | CHAR | 40 |  | Engineer Surname |
| 8 | `ZZTEL` | CHAR | 30 |  | Engineer Telephone |
| 9 | `ZZOPTOUT` | CHAR | 1 |  | Opt-out Indicator |
| 10 | `ZZAPPOINTMENTTDAT` | DATS | 8 |  | Date of Making Appointment |
| 11 | `ZZSITEINSPDAT` | DATS | 8 |  | Site Inspection Done On |
| 12 | `ZZNOTCONTOVER7DAT` | CHAR | 1 |  | Customer Can't Be Contacted Within 7 Days |
| 13 | `ZZCONTACTREMARK` | CHAR | 60 |  | Remarks |
| 14 | `ZZNOTSENDNOTICE` | CHAR | 1 |  | Do Not Send Customer is ready to make II Appt Noti to Cust |
| 15 | `ZZSITEWORKREQ` | CHAR | 1 |  | Site Work Required |
| 16 | `ZZOFFICERUSERID` | CHAR | 8 |  | Responsible Officer User ID |
| 17 | `ZZOFFICERNAME` | CHAR | 20 |  | Responsible Officer Name |
| 18 | `ZZOFFICERTEL` | CHAR | 20 |  | Responsible Officer Business Phone Number |

# ZISED_LPDEL_STAT
**Description:** Load Profile Service Deliver status
**Total Fields:** 34
**Key Fields:** MANDT, SEQNUM

## Programs Using This Table
- `zised0047`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQNUM` | NUMC | 15 | 🔑 | Sequence number |
| 3 | `REPORTDATE` | DATS | 8 |  | Reported Date |
| 4 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 5 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `SERVICETYPE` | CHAR | 2 |  | Load Profile Service Type |
| 9 | `LRTARIFTYP` | CHAR | 10 |  | Rate Category (Short) |
| 10 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 11 | `SERNR` | CHAR | 18 |  | Serial Number |
| 12 | `UNITOFMEASURE` | UNIT | 3 |  | Unit of measurement for meter reading |
| 13 | `READINGDATE` | DATS | 8 |  | Reading Date |
| 14 | `REQPROFILESTART` | DATS | 8 |  | Required Load Profile Start Date |
| 15 | `REQPROFILEEND` | DATS | 8 |  | Required Load Profile End Date |
| 16 | `PROFILEMISSININD` | CHAR | 1 |  | Profile Missing Indicator |
| 17 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 18 | `ABLESER` | CHAR | 3 |  | Meter reader number |
| 19 | `TEXT30` | CHAR | 30 |  | Text (30 Characters) |
| 20 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 21 | `ATWTB` | CHAR | 30 |  | Characteristic value description |
| 22 | `LPOSWORKDAY` | NUMC | 6 |  | Outstanding day of load profile (working day) |
| 23 | `LPOSDAY` | NUMC | 6 |  | Outstanding day of load profile (calender day) |
| 24 | `ACTUALRDINGDATE` | DATS | 8 |  | Actually Reading Date |
| 25 | `EINBDAT` | DATS | 8 |  | Installation date |
| 26 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 27 | `EFFDATE` | DATS | 8 |  | Effective date |
| 28 | `ISREVENUE` | CHAR | 1 |  | Revenue for bill |
| 29 | `ISCAACTIVE` | CHAR | 1 |  | CA active status |
| 30 | `EXISTINZDM135` | CHAR | 1 |  | Exists in ZDM135 |
| 31 | `ZDM135REMARK` | CHAR | 50 |  | Remark |
| 32 | `ISWORKINGDAY` | CHAR | 1 |  | Working Day |
| 33 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 34 | `ERZET` | TIMS | 6 |  | Entry time |

# ZISED_LPDEL_ACST
**Description:** Load Profile Service Deliver status - account lvl
**Total Fields:** 43
**Key Fields:** MANDT, REPORTDATE, VKONTO, SERVICETYPE, TARIFTYPSHORT

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORTDATE` | DATS | 8 | 🔑 | Reported Date |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SERVICETYPE` | CHAR | 2 | 🔑 | Load Profile Service Type |
| 5 | `TARIFTYPSHORT` | CHAR | 10 | 🔑 | Rate Category (Short) |
| 6 | `SLADATE` | DATS | 8 |  | SLA Date |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `MOLVIPCUSSEG` | CHAR | 1 |  | MOL-VIP Customer Segment |
| 9 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 10 | `ANLAGE` | CHAR | 10 |  | Installation |
| 11 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 12 | `UNITOFMEASURE` | UNIT | 3 |  | Unit of measurement for meter reading |
| 13 | `KWSACHSERVICELVL` | CHAR | 1 |  | KW Achieve Service Level |
| 14 | `KVAACHSERVICELVL` | CHAR | 1 |  | KVA Achieve Service Level |
| 15 | `READINGDATE` | DATS | 8 |  | Reading Date |
| 16 | `REQPROFILESTART` | DATS | 8 |  | Required Load Profile Start Date |
| 17 | `REQPROFILEEND` | DATS | 8 |  | Required Load Profile End Date |
| 18 | `ACHSERVICELVL` | CHAR | 1 |  | Achieved Service Level (e.g. Success, Failed) |
| 19 | `CUTOFFDATE` | DATS | 8 |  | Cut-off Date of Agreed Service Level |
| 20 | `AGINGSTATUS` | CHAR | 1 |  | 65+ days aging case - NFA, open, resolved & outstanding |
| 21 | `AGINGDAYS` | NUMC | 2 |  | Aging working days |
| 22 | `SERVCOMPWORKDAY` | NUMC | 2 |  | No. of Working days for service completion |
| 23 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 24 | `ABLESER` | CHAR | 3 |  | Meter reader number |
| 25 | `TEXT30` | CHAR | 30 |  | Text (30 Characters) |
| 26 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 27 | `ATWTB` | CHAR | 30 |  | Characteristic value description |
| 28 | `LPOSWORKDAY` | NUMC | 6 |  | Outstanding day of load profile (working day) |
| 29 | `LPOSDAY` | NUMC | 6 |  | Outstanding day of load profile (calender day) |
| 30 | `ACTUALRDINGDATE` | DATS | 8 |  | Actually Reading Date |
| 31 | `ACTUALBILLISSDATE` | DATS | 8 |  | Actual billing issue date |
| 32 | `LASTBILLISSDATE` | DATS | 8 |  | Last billing issue date |
| 33 | `EINBDAT` | DATS | 8 |  | Installation date |
| 34 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 35 | `EFFDATE` | DATS | 8 |  | Effective date |
| 36 | `ISREVENUE` | CHAR | 1 |  | Revenue for bill |
| 37 | `EXISTINZDM135` | CHAR | 1 |  | Exists in ZDM135 |
| 38 | `ZDM135REMARK` | CHAR | 50 |  | Remark |
| 39 | `ISWORKINGDAY` | CHAR | 1 |  | Working Day |
| 40 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 41 | `ERZET` | TIMS | 6 |  | Entry time |
| 42 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 43 | `AEZET` | TIMS | 6 |  | Time last change was made |

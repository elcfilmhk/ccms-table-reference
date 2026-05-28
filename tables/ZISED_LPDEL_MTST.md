# ZISED_LPDEL_MTST
**Description:** Load Profile Service Deliver status - meter lvl
**Total Fields:** 44
**Key Fields:** MANDT, REPORTDATE, SERNR, SERVICETYPE, TARIFTYPSHORT

## Programs Using This Table
- `zised0049`
- `zised0064`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORTDATE` | DATS | 8 | 🔑 | Reported Date |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `SERVICETYPE` | CHAR | 2 | 🔑 | Load Profile Service Type |
| 5 | `TARIFTYPSHORT` | CHAR | 10 | 🔑 | Rate Category (Short) |
| 6 | `SLADATE` | DATS | 8 |  | SLA Date |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `MOLVIPCUSSEG` | CHAR | 1 |  | MOL-VIP Customer Segment |
| 9 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 10 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 13 | `UNITOFMEASURE` | UNIT | 3 |  | Unit of measurement for meter reading |
| 14 | `KWSACHSERVICELVL` | CHAR | 1 |  | KW Achieve Service Level |
| 15 | `KVAACHSERVICELVL` | CHAR | 1 |  | KVA Achieve Service Level |
| 16 | `READINGDATE` | DATS | 8 |  | Reading Date |
| 17 | `REQPROFILESTART` | DATS | 8 |  | Required Load Profile Start Date |
| 18 | `REQPROFILEEND` | DATS | 8 |  | Required Load Profile End Date |
| 19 | `ACHSERVICELVL` | CHAR | 1 |  | Achieved Service Level (e.g. Success, Failed) |
| 20 | `CUTOFFDATE` | DATS | 8 |  | Cut-off Date of Agreed Service Level |
| 21 | `AGINGSTATUS` | CHAR | 1 |  | 65+ days aging case - NFA, open, resolved & outstanding |
| 22 | `AGINGDAYS` | NUMC | 2 |  | Aging working days |
| 23 | `SERVCOMPWORKDAY` | NUMC | 2 |  | No. of Working days for service completion |
| 24 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 25 | `ABLESER` | CHAR | 3 |  | Meter reader number |
| 26 | `TEXT30` | CHAR | 30 |  | Text (30 Characters) |
| 27 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 28 | `ATWTB` | CHAR | 30 |  | Characteristic value description |
| 29 | `LPOSWORKDAY` | NUMC | 6 |  | Outstanding day of load profile (working day) |
| 30 | `LPOSDAY` | NUMC | 6 |  | Outstanding day of load profile (calender day) |
| 31 | `ACTUALRDINGDATE` | DATS | 8 |  | Actually Reading Date |
| 32 | `ACTUALBILLISSDATE` | DATS | 8 |  | Actual billing issue date |
| 33 | `LASTBILLISSDATE` | DATS | 8 |  | Last billing issue date |
| 34 | `EINBDAT` | DATS | 8 |  | Installation date |
| 35 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 36 | `EFFDATE` | DATS | 8 |  | Effective date |
| 37 | `ISREVENUE` | CHAR | 1 |  | Revenue for bill |
| 38 | `EXISTINZDM135` | CHAR | 1 |  | Exists in ZDM135 |
| 39 | `ZDM135REMARK` | CHAR | 50 |  | Remark |
| 40 | `ISWORKINGDAY` | CHAR | 1 |  | Working Day |
| 41 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 42 | `ERZET` | TIMS | 6 |  | Entry time |
| 43 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 44 | `AEZET` | TIMS | 6 |  | Time last change was made |

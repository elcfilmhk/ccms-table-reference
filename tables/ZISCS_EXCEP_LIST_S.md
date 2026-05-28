# ZISCS_EXCEP_LIST_S
**Description:** BAPI structure for ZISCS_EXCEP_LISt table
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `ziscspc_bapi_excep_list=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `RECORD_ID` | NUMC | 10 |  | Record ID |
| 3 | `APPLICANT_NAME` | CHAR | 20 |  | Applicant Name |
| 4 | `HKID` | NUMC | 12 |  | HKID |
| 5 | `SCHOOL_CA_NUM` | CHAR | 12 |  | Contract Account Number |
| 6 | `SCHOOL_NAME` | CHAR | 40 |  | School Name |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 12 | `AEZET` | TIMS | 6 |  | Time last change was made |

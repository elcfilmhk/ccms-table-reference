# ZAEMFORM_HDR
**Description:** Header table as the destination storage to save the AEM Form
**Total Fields:** 13
**Key Fields:** MANDT, FORM_TRAN_ID

## Programs Using This Table
- `ziscs1121`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FORM_TRAN_ID` | CHAR | 12 | 🔑 | AEM form transaction ID |
| 3 | `FORM_TYPE` | CHAR | 30 |  | AEM form type |
| 4 | `REQ_DATETIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `STATUS` | CHAR | 1 |  | Status (N=New; P=Processed; F=Processed but sending Failed) |
| 6 | `ERROR_TYPE` | CHAR | 30 |  | Error Type |
| 7 | `ERROR_CODE` | CHAR | 20 |  | Error Code |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `ERZET` | TIMS | 6 |  | Entry time |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 13 | `AEZET` | TIMS | 6 |  | Time last change was made |

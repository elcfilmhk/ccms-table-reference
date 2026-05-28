# ZIS_EEC_SO_DET
**Description:** EEC specific Enhancement Fields
**Total Fields:** 39
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0507`
- `ziscs0514`
- `ziscs0838`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `RES_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 4 | `NA_USERID` | CHAR | 12 |  | User Name in User Master Record |
| 5 | `NA_SURNAME` | CHAR | 40 |  | Last name |
| 6 | `NA_TEL` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 7 | `NA_MAIL` | CHAR | 30 |  | Email |
| 8 | `SA_USERID` | CHAR | 12 |  | User Name in User Master Record |
| 9 | `SA_SURNAME` | CHAR | 40 |  | Last name |
| 10 | `SA_TEL` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 11 | `SA_MAIL` | CHAR | 30 |  | Email |
| 12 | `SITEWORKREQ` | CHAR | 1 |  | Site Work Required |
| 13 | `APPOINTMENTTDAT` | DATS | 8 |  | Date of Making Appointment |
| 14 | `SITEINSPDAT` | DATS | 8 |  | Site Inspection Done On |
| 15 | `REASON` | CHAR | 40 |  | Reasons for Delay of site test witness |
| 16 | `REMARK` | CHAR | 60 |  | Remarks |
| 17 | `MAX_CAP_ALLOWED` | QUAN | 9 |  | Maximum Allowable Capacity(kW) |
| 18 | `NASF_REASON1_CODE` | CHAR | 2 |  | NASF Reason |
| 19 | `NASF_REASON2_CODE` | CHAR | 2 |  | NASF Reason |
| 20 | `NASF_REASON3_CODE` | CHAR | 2 |  | NASF Reason |
| 21 | `NASF_REASON4_CODE` | CHAR | 2 |  | NASF Reason |
| 22 | `NASF_REASON5_CODE` | CHAR | 2 |  | NASF Reason |
| 23 | `NASF_REASON6_CODE` | CHAR | 2 |  | NASF Reason |
| 24 | `NASF_REASON7_CODE` | CHAR | 2 |  | NASF Reason |
| 25 | `NASF_REASON8_CODE` | CHAR | 2 |  | NASF Reason |
| 26 | `NASF_REASON9_CODE` | CHAR | 2 |  | NASF Reason |
| 27 | `NASF_REASON10_CODE` | CHAR | 2 |  | NASF Reason |
| 28 | `NASF_REMARK` | CHAR | 128 |  | First 128 characters of NASF Remark |
| 29 | `CHANGE_FIT` | CHAR | 2 |  | Customer Change FiT Application |
| 30 | `CHANGE_INST` | CHAR | 2 |  | Customer Installation Modification |
| 31 | `SCOPE_WORK` | CHAR | 2 |  | CLP Work Scope |
| 32 | `LEAD_TIME` | CHAR | 3 |  | Estimated Lead time |
| 33 | `REMARKS2` | CHAR | 100 |  | Remarks Long Text (First 100 Chars) |
| 34 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 35 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 36 | `ERZET` | TIMS | 6 |  | Entry time |
| 37 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 38 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 39 | `AEZET` | TIMS | 6 |  | Time last change was made |

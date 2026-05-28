# ZISBIVDIPELTR
**Description:** VoltDipEnquiry Correspondence Outbox & History
**Total Fields:** 33
**Key Fields:** MANDT, BATCH_RUN_DATE, CASE_ID, DRAFT

## Programs Using This Table
- `zisbi0199`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch Run Date 1 |
| 3 | `CASE_ID` | NUMC | 8 | 🔑 | VoltDipEnquiry case ID |
| 4 | `DRAFT` | CHAR | 1 | 🔑 | Single-Character Flag |
| 5 | `CHANNEL` | CHAR | 10 |  | Reply Channel |
| 6 | `EBILL_SENDER` | CHAR | 100 |  | Email sender address name |
| 7 | `EMAIL` | CHAR | 200 |  | Customer Email Address |
| 8 | `CCEMAIL` | CHAR | 200 |  | Customer Email Address |
| 9 | `FAX` | CHAR | 30 |  | First fax no.: dialling code+number |
| 10 | `LANG` | LANG | 1 |  | Language Key |
| 11 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 12 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `ERZET` | TIMS | 6 |  | Entry time |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 17 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 18 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 19 | `COMP_NAME` | CHAR | 100 |  | Company Name of customer |
| 20 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 21 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 22 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 23 | `STREET` | CHAR | 60 |  | Street |
| 24 | `CITY2` | CHAR | 40 |  | District |
| 25 | `CITY1` | CHAR | 40 |  | City |
| 26 | `LTTR_RCPT_NAME` | CHAR | 100 |  | Recipient Name as displayed on letter |
| 27 | `LTTR_REF` | CHAR | 80 |  | Reference Number as displayed on letter |
| 28 | `LTTR_SUBJ_TEXT` | CHAR | 200 |  | Letter Subject Header Text |
| 29 | `INCD_VOLT_LV` | CHAR | 50 |  | Voltage Level text as displayed on letter |
| 30 | `INCD_DT` | CHAR | 14 |  | Investigation Result: Incident datetime |
| 31 | `LTTR_ACC_MGR_NAME` | CHAR | 100 |  | AM name as displayed on letter |
| 32 | `LTTR_ACC_MGR_TEL` | CHAR | 30 |  | AM Telephone as displayed on letter |
| 33 | `PDF_FILENAME` | CHAR | 100 |  | Filename used by VoltDipEnquiry |

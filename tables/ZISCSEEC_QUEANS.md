# ZISCSEEC_QUEANS
**Description:** Config: Questionnaire Questions and Answers
**Total Fields:** 20
**Key Fields:** MANDT, QUE_SET_ID, QUE_ID, ANS_ID, QUE_SET_VER

## Programs Using This Table
- `ziscs0381_eec`
- `ziscs0383_eec`
- `ziscs0386_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUE_SET_ID` | CHAR | 50 | 🔑 | Question Set (Questionnaire) ID |
| 3 | `QUE_ID` | CHAR | 50 | 🔑 | Question ID |
| 4 | `ANS_ID` | CHAR | 50 | 🔑 | Answer ID |
| 5 | `QUE_SET_VER` | CHAR | 20 | 🔑 | Questionnaire Version |
| 6 | `EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 9 | `TYPE` | CHAR | 1 |  | 'Q'uestion ; 'A'nswer |
| 10 | `SEQ` | INT4 | 10 |  | Natural number |
| 11 | `RECOMMENDED_ANS` | CHAR | 1 |  | 'X': Recommended Answer |
| 12 | `TEXT_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 13 | `TEXT_ZF` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 14 | `MIN_ANS` | INT4 | 10 |  | Natural number |
| 15 | `MAX_ANS` | INT4 | 10 |  | Natural number |
| 16 | `ANS_VALUE_EDIT` | NUMC | 2 |  | 1: LO only; 2: LO and HI; Others: Not Editable |
| 17 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 18 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 20 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |

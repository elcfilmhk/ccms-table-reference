# ZISCS_EEC_QUESTNAIRE_A_LIST
**Description:** List of Questionaire Answers
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0383_eec`
- `ziscs0386_eec`
- `ziscseec_ep_get_quiz_ws=======ft`
- `ziscseec_get_queans===========ft`
- `ziscseec_get_queans_ws========ft`
- `ziscseec_save_answers_ws======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `QUE_SET_ID` | CHAR | 50 |  | Question Set (Questionnaire) ID |
| 2 | `QUE_ID` | CHAR | 50 |  | Question ID |
| 3 | `ANS_ID` | CHAR | 50 |  | Answer ID |
| 4 | `SEQ` | INT4 | 10 |  | Natural number |
| 5 | `RECOMMENDED_ANS` | CHAR | 1 |  | Single-Character Flag |
| 6 | `ANS_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 8 | `TEXT_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 9 | `TEXT_ZF` | CHAR | 300 |  | Text length 300 |
| 10 | `ANS_VALUE_EDIT` | NUMC | 2 |  | 1: LO only; 2: LO and HI; Others: Not Editable |
| 11 | `ANS_VALUE_LO` | CHAR | 300 |  | Answer Value |
| 12 | `ANS_VALUE_HI` | CHAR | 300 |  | Answer Value |

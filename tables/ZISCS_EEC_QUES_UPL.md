# ZISCS_EEC_QUES_UPL
**Description:** Questionnaire Up/Download
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0381_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `QUE_SET_ID` | CHAR | 100 |  | Question Set (Questionnaire) ID |
| 2 | `QUE_SET_VER` | CHAR | 300 |  | Questionnaire Version |
| 3 | `TYPE` | CHAR | 100 |  | 'Q'uestion ; 'A'nswer |
| 4 | `QUE_ID` | CHAR | 100 |  | Question ID |
| 5 | `ANS_ID` | CHAR | 100 |  | Answer ID |
| 6 | `EFF_FM_DT` | CHAR | 30 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `EFF_EXP_DT` | CHAR | 30 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `IMAGE_CODE` | CHAR | 40 |  | Image Code |
| 9 | `SEQ` | CHAR | 30 |  | Natural Number |
| 10 | `RECOMMENDED_ANS` | CHAR | 2 |  | 'X': Recommended Answer |
| 11 | `TEXT_EN` | CHAR | 600 |  | Display Text (English) |
| 12 | `TEXT_EN2` | CHAR | 600 |  | Display Text (English) |
| 13 | `TEXT_ZF` | CHAR | 600 |  | Display Text (Chinese Traditional) |
| 14 | `TEXT_ZF2` | CHAR | 600 |  | Display Text (Chinese Traditional) |
| 15 | `MIN_ANS` | CHAR | 30 |  | Natural Number |
| 16 | `MAX_ANS` | CHAR | 30 |  | Natural Number |
| 17 | `ANS_VALUE_EDIT` | CHAR | 100 |  | 1: LO only; 2: LO and HI; Others: Not Editable |

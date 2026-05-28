# ZISCSEEC_CAANSW
**Description:** Stores CA's answers for questionnaires
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, QUE_SET_ID, QUE_ID, EFF_FM_DT, ANS_ID

## Programs Using This Table
- `ziscs0383_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `QUE_SET_ID` | CHAR | 50 | 🔑 | Question Set (Questionnaire) ID |
| 4 | `QUE_ID` | CHAR | 50 | 🔑 | Question ID |
| 5 | `EFF_FM_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `ANS_ID` | CHAR | 50 | 🔑 | Answer ID |
| 7 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `ANS_VALUE_LO` | CHAR | 300 |  | Answer Value |
| 9 | `ANS_VALUE_HI` | CHAR | 300 |  | Answer Value |

# ZISBIEDELIVERYC
**Description:** Config table for e-Delivery
**Total Fields:** 9
**Key Fields:** MANDT, LETTER_TITLE

## Programs Using This Table
- `zisbi0180`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LETTER_TITLE` | CHAR | 30 | 🔑 | Letter Title |
| 3 | `LETTER_ID` | CHAR | 2 |  | Letter ID |
| 4 | `MSGTEXT_ID` | CHAR | 30 |  | Message Text ID |
| 5 | `SORTKEY` | NUMC | 5 |  | Sorting Order |
| 6 | `SEQ_NO` | CHAR | 2 |  | Sequence No |
| 7 | `APPENDIX` | CHAR | 1 |  | Failed records display in appendix |
| 8 | `LETTER_NAME` | CHAR | 40 |  | Letter Name |
| 9 | `MSGTEXTNUM` | CHAR | 1 |  | Position of Message Text captured for failed records |

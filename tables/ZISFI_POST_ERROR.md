# ZISFI_POST_ERROR
**Description:** Rebate Refund Message Log
**Total Fields:** 10
**Key Fields:** MANDT, LOG_REF, RB_YEAR, VKONT, VERTRAG, SEQ_NO

## Programs Using This Table
- `zisbi0201_ind`
- `zisbi0201_mu`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOG_REF` | CHAR | 50 | 🔑 | Reference |
| 3 | `RB_YEAR` | CHAR | 8 | 🔑 | Rebate year and reference |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 6 | `SEQ_NO` | NUMC | 3 | 🔑 | Seq No. |
| 7 | `MESSAGE_TEXT` | CHAR | 220 |  | Message Text |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

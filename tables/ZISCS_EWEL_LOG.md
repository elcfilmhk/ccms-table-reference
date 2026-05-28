# ZISCS_EWEL_LOG
**Description:** Trigger ewelcome letter upon MI completion log
**Total Fields:** 8
**Key Fields:** MANDT, CREATION_DT, EINZBELEG, SEQ_NO

## Programs Using This Table
- `ziscs0550`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREATION_DT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `EINZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-in document |
| 4 | `SEQ_NO` | CHAR | 2 | 🔑 | Sequence No |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `STAFF_ID` | CHAR | 12 |  | User Name |
| 7 | `STATUS` | CHAR | 1 |  | Status |
| 8 | `MESSAGE` | CHAR | 220 |  | Message Text |

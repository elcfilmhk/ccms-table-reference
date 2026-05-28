# ZISCSSER_CONTSER
**Description:** Table to store linkage between eService and contact
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, TYPE, DISPATCH, ITEM

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 4 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 5 | `ITEM` | CHAR | 10 | 🔑 | Item Number for Contact Number |
| 6 | `STATUS` | CHAR | 1 |  | Status |
| 7 | `REC_NOTIFICATION` | CHAR | 1 |  | 'X': Receive Notifications; others: not |

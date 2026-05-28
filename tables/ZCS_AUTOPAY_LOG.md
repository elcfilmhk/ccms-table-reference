# ZCS_AUTOPAY_LOG
**Description:** Record about Create autopay application
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, ZZTRAN_ID

## Programs Using This Table
- `ziscs1133`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ZZTRAN_ID` | CHAR | 10 | 🔑 | CRM activity ID |
| 4 | `ZCREATEDT` | CHAR | 14 |  | Datetime of create data |
| 5 | `ZZTRANSDT` | CHAR | 14 |  | Datetime of updating payment method |
| 6 | `STATUS` | CHAR | 1 |  | Updating Status |
| 7 | `MSGTX` | CHAR | 100 |  | Message text |
| 8 | `ZCOUNT` | NUMC | 3 |  | Counter |

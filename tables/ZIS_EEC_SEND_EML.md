# ZIS_EEC_SEND_EML
**Description:** Sender Email address for activity code
**Total Fields:** 7
**Key Fields:** MANDT, ACT_CODE, WORK_CENTER, RATE_TYPE

## Programs Using This Table
- `ziscrm0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACT_CODE` | CHAR | 25 | 🔑 | Activity code |
| 3 | `WORK_CENTER` | CHAR | 8 | 🔑 | Work Center |
| 4 | `RATE_TYPE` | CHAR | 40 | 🔑 | Rate Type |
| 5 | `SENDER` | CHAR | 50 |  | Email ID |
| 6 | `SENDER_NAME_EN` | CHAR | 100 |  | Sender Name English |
| 7 | `SENDER_NAME_CH` | CHAR | 100 |  | Sender Name Chinese |

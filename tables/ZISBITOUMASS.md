# ZISBITOUMASS
**Description:** TOU Charge Type Master
**Total Fields:** 9
**Key Fields:** MANDT, SCHEME, CHARGE_TYPE

## Programs Using This Table
- `zisbi0271`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME` | CHAR | 4 | 🔑 | EV TOU Scheme |
| 3 | `CHARGE_TYPE` | CHAR | 4 | 🔑 | TOU Charge Type |
| 4 | `ZF_CHARGE_DESC1` | CHAR | 50 |  | ZF Charge Description 1 |
| 5 | `ZF_CHARGE_DESC2` | CHAR | 50 |  | ZF Charge Description 2 |
| 6 | `EN_CHARGE_DESC1` | CHAR | 50 |  | EN Charge Description 1 |
| 7 | `EN_CHARGE_DESC2` | CHAR | 50 |  | EN Charge Description 2 |
| 8 | `EV_CHARGE` | DEC | 17 |  | EV TOU Energy Consumption Charge |
| 9 | `GST_CHARGE` | DEC | 17 |  | GST Energy Consumption Charge |

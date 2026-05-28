# ZISCSPC_ACT_BDG
**Description:** EEC CA Action to Power Connect Incentive Mapping
**Total Fields:** 6
**Key Fields:** MANDT, EEC_CMPG_CODE, EEC_CMPG_ACTN_CODE, SEQ

## Programs Using This Table
- `ziscspc_eec_action_badges`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EEC_CMPG_CODE` | CHAR | 50 | 🔑 | EE&C Campaign Code |
| 3 | `EEC_CMPG_ACTN_CODE` | CHAR | 50 | 🔑 | EE&C Campaign Action Code |
| 4 | `SEQ` | INT2 | 5 | 🔑 | 2 byte integer (signed) |
| 5 | `INCENTIVE_TYPE` | CHAR | 10 |  | Incentive Type |
| 6 | `INCENTIVE_CODE` | CHAR | 4 |  | Incentive Code |

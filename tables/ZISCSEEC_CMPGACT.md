# ZISCSEEC_CMPGACT
**Description:** EE&C Campaign Actions Master
**Total Fields:** 12
**Key Fields:** MANDT, EEC_CMPG_CODE, EEC_CMPG_ACTN_CODE

## Programs Using This Table
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0390_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EEC_CMPG_CODE` | CHAR | 50 | 🔑 | EE&C Campaign Code |
| 3 | `EEC_CMPG_ACTN_CODE` | CHAR | 50 | 🔑 | EE&C Campaign Action Code |
| 4 | `EEC_CMPG_ACTN_NAME` | CHAR | 100 |  | EE&C Action Name |
| 5 | `DESC1_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 6 | `DESC1_ZF` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 7 | `CRM_ACT_PROCESS_TY` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 8 | `CRM_ACT_CATEGORY` | CHAR | 3 |  | 3-Byte field |
| 9 | `CRM_ACT_CODE_GRP` | CHAR | 8 |  | Code Group |
| 10 | `CRM_ACTIVITY_CODE` | CHAR | 4 |  | Code |
| 11 | `EP_TRANS_REASON` | CHAR | 50 |  | Eco Points Transaction Reason |
| 12 | `EP_TRANS_AMT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |

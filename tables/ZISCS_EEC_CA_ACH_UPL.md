# ZISCS_EEC_CA_ACH_UPL
**Description:** EE&C Achievement Up/Download
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0388_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 15 |  | Contract Account |
| 2 | `EEC_CMPG_CODE` | CHAR | 70 |  | EE&C Campaign Code |
| 3 | `EEC_CMPG_ACHV_CODE` | CHAR | 70 |  | EE&C Campaign Achievement Code |
| 4 | `EFF_FM_DT` | CHAR | 30 |  | Effective Date |
| 5 | `REVOKE_FLAG` | CHAR | 2 |  | {Blank}: Award; 'X': Revoke the Achievement |
| 6 | `REASON` | CHAR | 70 |  | Reward/Invoke Reason |

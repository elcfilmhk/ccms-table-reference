# ZREG_CONVERSION_OUTPUT
**Description:** Registers to be Converted data-rate/ prof/rel bill indicator
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0203_cbtolp`
- `zisdm0203_rbtolp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 2 | `DEVICE` | CHAR | 18 |  | Serial Number |
| 3 | `REGISTOR` | CHAR | 3 |  | 3-Byte field |
| 4 | `SCENARIO` | CHAR | 20 |  | Scenario |
| 5 | `METERROLE` | CHAR | 50 |  | Comment |
| 6 | `RATETYPE` | CHAR | 8 |  | Rate type |
| 7 | `BILL_REL_INDICATOR` | CHAR | 1 |  | New Billing Relevant indicator |
| 8 | `NEW_RATE_TYPE` | CHAR | 8 |  | New rate type |
| 9 | `NEW_BILL_RELEVANT_INDICATOR` | CHAR | 1 |  | New Billing Relevant indicator |
| 10 | `NEW_PROFILE_ROLE` | CHAR | 4 |  | New profile role |
| 11 | `EXISTING_PROF` | CHAR | 4 |  | Profile allocation role |
| 12 | `EXISTING_NO_MR_INDICATOR` | CHAR | 1 |  | Existing No MR indicator |
| 13 | `NEW_NO_MR_INDICATOR` | CHAR | 1 |  | New No MR indicator |

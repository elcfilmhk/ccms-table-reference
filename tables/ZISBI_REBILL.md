# ZISBI_REBILL
**Description:** Installation result whether to be rebill or not
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0262`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 2 | `VALIDATION_RESULT` | CHAR | 1 |  | 0:False(Not reverse/rebill) 1:True(Reverse/Rebill)scenario |
| 3 | `SCH_BILLINGDATE` | DATS | 8 |  | Scheduled Billing Date |

# ZISCSSELFBILL
**Description:** Self-selected billing date created by Billing members
**Total Fields:** 5
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs0158`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `EFFDATE` | DATS | 8 |  | Effective Date |
| 4 | `USERNAME` | CHAR | 12 |  | Created By |
| 5 | `REMARKS` | CHAR | 50 |  | Remarks |

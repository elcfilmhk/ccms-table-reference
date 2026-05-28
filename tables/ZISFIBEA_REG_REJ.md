# ZISFIBEA_REG_REJ
**Description:** BEA Rejected Registration
**Total Fields:** 6
**Key Fields:** MANDT, REGID, ITEM_NO, REASON_CODE

## Programs Using This Table
- `zisfi0254`
- `zisfi0256`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGID` | CHAR | 10 | 🔑 | BEA Register ID |
| 3 | `ITEM_NO` | NUMC | 3 | 🔑 | Item Number |
| 4 | `REASON_CODE` | NUMC | 3 | 🔑 | Reject Reason Code |
| 5 | `BYPASS` | CHAR | 1 |  | by-Pass |
| 6 | `REASON` | CHAR | 255 |  | Reject Reason |

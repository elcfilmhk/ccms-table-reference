# ZISSDSOCHGDETAIL
**Description:** Sales Order Change Details
**Total Fields:** 7
**Key Fields:** MANDT, VBELN, POSNR, CHANGE_DATE, CHANGE_TIME, CHANGE_REASON, SEQ_NO

## Programs Using This Table
- `zissd00088`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VBELN` | CHAR | 10 | 🔑 | Sales Document |
| 3 | `POSNR` | NUMC | 6 | 🔑 | Sales Document Item |
| 4 | `CHANGE_DATE` | DATS | 8 | 🔑 | Change Date |
| 5 | `CHANGE_TIME` | TIMS | 6 | 🔑 | Change Time |
| 6 | `CHANGE_REASON` | CHAR | 2 | 🔑 | Change Reason |
| 7 | `SEQ_NO` | NUMC | 3 | 🔑 | Sequence Number |

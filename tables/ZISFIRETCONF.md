# ZISFIRETCONF
**Description:** Configuration table for payment return program
**Total Fields:** 15
**Key Fields:** MANDT, ZCHANNEL_ID

## Programs Using This Table
- `zisfi0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZCHANNEL_ID` | CHAR | 5 | 🔑 | Channel ID |
| 3 | `ZCHANNEL` | CHAR | 50 |  | Channel Name |
| 4 | `ZFROM_DATE` | DATS | 8 |  | Valid From Date |
| 5 | `ZTO_DATE` | DATS | 8 |  | Valid To Date |
| 6 | `ZCAL_ID` | CHAR | 2 |  | Calendar ID |
| 7 | `ZHEADER_VDV` | CHAR | 2 |  | Header-value date Variance |
| 8 | `ZITEM_DV` | CHAR | 2 |  | Item-Posting Date Variance |
| 9 | `ZITEM_VDV` | CHAR | 2 |  | Item-value date variance |
| 10 | `ZHC_CRGL_ACC` | CHAR | 10 |  | HC-Cr GL Account |
| 11 | `ZHC_CRBUS_AREA` | CHAR | 5 |  | HC CRbus area |
| 12 | `ZHC_DRGL_ACC` | CHAR | 15 |  | HC DrGL account |
| 13 | `ZHC_DRBUS_AREA` | CHAR | 5 |  | HC DRbus area |
| 14 | `ZCOST_CENTER` | CHAR | 10 |  | COST CENTER |
| 15 | `ZHC_DATEVAR` | CHAR | 2 |  | HC-Date Variance |

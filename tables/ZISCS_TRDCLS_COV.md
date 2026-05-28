# ZISCS_TRDCLS_COV
**Description:** Cont Acc trade cat, trade class, prem func conversion count
**Total Fields:** 5
**Key Fields:** MANDT, UPLOAD_DATE, UPLOAD_TIME

## Programs Using This Table
- `ziscs0279`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UPLOAD_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `UPLOAD_TIME` | TIMS | 6 | 🔑 | Field of type TIMS |
| 4 | `USER_ID` | CHAR | 12 |  | User Name |
| 5 | `ZCOUNT` | INT4 | 10 |  | Whole Number with +/- Sign (-2.147.483.648 .. 2.147.483.647) |

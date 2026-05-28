# ZISBI_TRHOLD_AMT
**Description:** Threshold Amount of Billing Txns for Diff Rate Categories
**Total Fields:** 13
**Key Fields:** MANDT, TARIFTYP, BILL_TRANS, AB

## Programs Using This Table
- `zisbi0042`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `BILL_TRANS` | CHAR | 2 | 🔑 | Billing Transaction |
| 4 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 5 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 6 | `MIN_ALLOWED` | CURR | 13 |  | Minimum Allowable Amount |
| 7 | `MAX_ALLOWED` | CURR | 13 |  | Maximum Allowable Amount |
| 8 | `MIN_CREDIT` | CURR | 13 |  | Minimum Credit Amount |
| 9 | `MAX_CREDIT` | CURR | 13 |  | Maximum Credit Amount |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

# ZISFISTDDM
**Description:** Custom Table for RFI16 (TC ZFI16) - Direct Debit Movement
**Total Fields:** 14
**Key Fields:** MANDT, SPMON, GJAHR, REVNO, ROWNO

## Programs Using This Table
- `zisfi0039`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SPMON` | NUMC | 2 | 🔑 | Month of the report |
| 3 | `GJAHR` | NUMC | 4 | 🔑 | Year of the report |
| 4 | `REVNO` | NUMC | 2 | 🔑 | Revision Number |
| 5 | `ROWNO` | CHAR | 3 | 🔑 | Line Number |
| 6 | `COL01` | DEC | 13 |  | Column 1 (LPT) |
| 7 | `COL02` | DEC | 13 |  | Column 2 (BT) |
| 8 | `COL03` | DEC | 13 |  | Column 3 (GST) |
| 9 | `COL04` | DEC | 13 |  | Column 4 (DT) |
| 10 | `COL05` | DEC | 13 |  | Column 5 (Total) |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `COL06` | DEC | 13 |  | Column 6 (EV_FLAT) |
| 14 | `COL07` | DEC | 13 |  | Column7(EV_TOU) |

# ZISBI_ADJ_SUMY_RPT
**Description:** Adjusted Bill Summary Report
**Total Fields:** 46
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PERIOD_FR` | DATS | 8 |  | Report Period From |
| 2 | `PERIOD_TO` | DATS | 8 |  | Report Period to |
| 3 | `RPT_SECTION` | CHAR | 40 |  | Section |
| 4 | `ADJ_REATYPE` | CHAR | 50 |  | Adjustment Reason Type |
| 5 | `ADJ_REASON` | CHAR | 45 |  | Adjustment Reason |
| 6 | `ADJ_DEBIT` | CURR | 13 |  | Total Adjustment Debit Amount |
| 7 | `ADJ_CREDIT` | CURR | 13 |  | Total Adjustment Credit Amount |
| 8 | `BRANCH` | CHAR | 12 |  | Branch |
| 9 | `BNAME` | CHAR | 12 |  | User Name in User Master Record |
| 10 | `FULL_NAME` | CHAR | 80 |  | Full Name of Person |
| 11 | `BUS_POST` | CHAR | 80 |  | Business Position |
| 12 | `ADJ_STAT` | CHAR | 30 |  | Adjustment Statistics |
| 13 | `NR_CASE` | INT4 | 10 |  | No. of cases |
| 14 | `MB_WI` | INT4 | 10 |  | Manual Bill Within |
| 15 | `MB_OS` | INT4 | 10 |  | Manual Bill Outside |
| 16 | `MB_TOT` | INT4 | 10 |  | Manual Bill Total |
| 17 | `ADJ_WI` | INT4 | 10 |  | Adjustment Within |
| 18 | `ADJ_OS` | INT4 | 10 |  | Adjustment  Outside |
| 19 | `ADJ_TOT` | INT4 | 10 |  | Adjustment Total |
| 20 | `ISO_WI` | INT4 | 10 |  | ISO Within |
| 21 | `ISO_OS` | INT4 | 10 |  | ISO Outside |
| 22 | `ISO_TOT` | INT4 | 10 |  | ISO Total |
| 23 | `BC_WI` | INT4 | 10 |  | Backcharge Within |
| 24 | `BC_OS` | INT4 | 10 |  | Backcharge Outside |
| 25 | `BC_TOT` | INT4 | 10 |  | Backcharge Total |
| 26 | `UM_WI` | INT4 | 10 |  | Unmetered Within |
| 27 | `UM_OS` | INT4 | 10 |  | Unmetered Outside |
| 28 | `UM_TOT` | INT4 | 10 |  | Unmetered Total |
| 29 | `STD_WI` | INT4 | 10 |  | Standard Within |
| 30 | `STD_OS` | INT4 | 10 |  | Standard Outside |
| 31 | `STD_TOT` | INT4 | 10 |  | Standard Total |
| 32 | `MB_INIT` | INT4 | 10 |  | Manual Bill Init |
| 33 | `MB_APPR` | INT4 | 10 |  | Manual Bill Appr |
| 34 | `MB_INAP` | INT4 | 10 |  | Manual Bill Init & Appr |
| 35 | `ADJ_INIT` | INT4 | 10 |  | Adjustment Init |
| 36 | `ADJ_APPR` | INT4 | 10 |  | Adjustment Appr |
| 37 | `ADJ_INAP` | INT4 | 10 |  | Adjustment Init & Appr |
| 38 | `BC_INIT` | INT4 | 10 |  | Backcharge Init |
| 39 | `BC_APPR` | INT4 | 10 |  | Backcharge Appr |
| 40 | `BC_INAP` | INT4 | 10 |  | Backcharge Init & Appr |
| 41 | `UM_INIT` | INT4 | 10 |  | Unmeterd Init |
| 42 | `UM_APPR` | INT4 | 10 |  | Unmeterd Appr |
| 43 | `UM_INAP` | INT4 | 10 |  | Unmeterd Init & Appr |
| 44 | `TOT_INIT` | INT4 | 10 |  | Total Init |
| 45 | `TOT_APPR` | INT4 | 10 |  | Total Appr |
| 46 | `TOT_INAP` | INT4 | 10 |  | Total Init & Appr |

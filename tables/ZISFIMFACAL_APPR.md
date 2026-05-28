# ZISFIMFACAL_APPR
**Description:** FCC Value Approval
**Total Fields:** 38
**Key Fields:** MANDT, TARIFF_YEAR, TARIFF_MONTH, VERSION

## Programs Using This Table
- `zisfi0297`
- `zisfi0298`
- `zisfi0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFF_YEAR` | NUMC | 4 | 🔑 | Tariff Year |
| 3 | `TARIFF_MONTH` | NUMC | 2 | 🔑 | Tariff Month |
| 4 | `VERSION` | NUMC | 2 | 🔑 | Version |
| 5 | `REFERENCE_COAL_COST` | DEC | 23 |  | Reference Coal Cost |
| 6 | `REFERENCE_GAS_COST` | DEC | 23 |  | Reference Gas Cost |
| 7 | `REFERENCE_OIL_COST` | DEC | 23 |  | Reference Oil Cost |
| 8 | `AVERAGE_COAL_PRICE` | DEC | 23 |  | Average Coal Price |
| 9 | `AVERAGE_GAS_PRICE` | DEC | 23 |  | Average Gas Price |
| 10 | `AVERAGE_OIL_PRICE` | DEC | 23 |  | Average Oil Price |
| 11 | `COAL_PRICE_CHANGE` | DEC | 23 |  | Change in Coal Price |
| 12 | `GAS_PRICE_CHANGE` | DEC | 23 |  | Change in Gas Price |
| 13 | `OIL_PRICE_CHANGE` | DEC | 23 |  | Change in Oil Price |
| 14 | `COAL_MONTH_ADJ` | DEC | 23 |  | Monthly Adjustment for Coal |
| 15 | `GAS_MONTH_ADJ` | DEC | 23 |  | Monthly Adjustment for Gas |
| 16 | `OIL_MONTH_ADJ` | DEC | 23 |  | Monthly Adjustment for Oil |
| 17 | `ADJUSTED_VALUE` | DEC | 23 |  | Monthly Adjusted Value |
| 18 | `TOTAL_FCC` | DEC | 23 |  | Fuel Clause Charge |
| 19 | `TRIGGER_APPROVAL` | CHAR | 1 |  | Trigger Approval |
| 20 | `LATEST_APPROVAL_LEVEL` | NUMC | 2 |  | Approval Level |
| 21 | `LATEST_APPROVAL_BY` | CHAR | 12 |  | Approval By |
| 22 | `LATEST_APPROVAL_DATE` | DATS | 8 |  | Approval Date |
| 23 | `LATEST_APPROVAL_TIME` | TIMS | 6 |  | Approval Time |
| 24 | `REJECTED_LEVEL` | NUMC | 2 |  | Rejected Level |
| 25 | `REJECTED_BY` | CHAR | 12 |  | Rejected By |
| 26 | `REJECTED_DATE` | DATS | 8 |  | Rejected Date |
| 27 | `REJECTED_TIME` | TIMS | 6 |  | Rejected Time |
| 28 | `REVERSED_LEVEL` | NUMC | 2 |  | Reversed Level |
| 29 | `REVERSED_BY` | CHAR | 12 |  | Reversed By |
| 30 | `REVERSED_DATE` | DATS | 8 |  | Reversed Date |
| 31 | `REVERSED_TIME` | TIMS | 6 |  | Reversed Time |
| 32 | `APPROVED_FLAG` | CHAR | 1 |  | Approved Flag |
| 33 | `REJECTED_FLAG` | CHAR | 1 |  | Rejected Flag |
| 34 | `REVERSED_FLAG` | CHAR | 1 |  | Reversed Flag |
| 35 | `PARTIAL_REJECTED_FLAG` | CHAR | 1 |  | Partial Rejected Flag |
| 36 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 37 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 38 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

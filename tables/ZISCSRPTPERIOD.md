# ZISCSRPTPERIOD
**Description:** Report execution period
**Total Fields:** 4
**Key Fields:** MANDT, START_MONTH

## Programs Using This Table
- `ziscs0228`
- `ziscs0229`
- `ziscs0268`
- `ziscs0269`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `START_MONTH` | CHAR | 2 | 🔑 | Reporting Start Month |
| 3 | `PERIOD` | NUMC | 2 |  | Report Period |
| 4 | `PERIOD_DESC` | CHAR | 20 |  | Report Period Description |

# ZISBISEGCT
**Description:** Budget Billing CA segment count by month
**Total Fields:** 6
**Key Fields:** MANDT, PERIOD, TARIFTYP, SEGMENT, STATUS

## Programs Using This Table
- `zisbi0079`
- `zisbi0080`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | ACCP | 6 | 🔑 | Posting period in the form YYYYMM |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `SEGMENT` | CHAR | 1 | 🔑 | Segment label |
| 5 | `STATUS` | CHAR | 1 | 🔑 | Budget billing payment plan status |
| 6 | `CA_COUNT` | INT4 | 10 |  | number of CA for each segment |

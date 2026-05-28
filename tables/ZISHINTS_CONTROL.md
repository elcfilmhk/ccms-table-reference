# ZISHINTS_CONTROL
**Description:** Hints Control for Performance
**Total Fields:** 4
**Key Fields:** MANDT, FNAME

## Programs Using This Table
- `zrmrd_fulfilment_day`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FNAME` | CHAR | 30 | 🔑 | Name of Function Module |
| 3 | `HINTS_CONTROL` | CHAR | 1 |  | Customizing Hints Control |
| 4 | `SPEC_HINTS` | CHAR | 100 |  | Specific Hints in table |

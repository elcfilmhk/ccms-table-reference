# ZISEDILPCRPT
**Description:** Interval Load Profile Counting Report
**Total Fields:** 7
**Key Fields:** MANDT, SERNR, PROFILE, PRODATE

## Programs Using This Table
- `zised0062`
- `zised0063`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 4 | `PRODATE` | DATS | 8 | 🔑 | Day of profile values |
| 5 | `INTERVALMISSCNT` | INT1 | 3 |  | Interval Missing Count |
| 6 | `STATUS` | NUMC | 2 |  | Status |
| 7 | `IDX_READ` | CHAR | 1 |  | Index Reading Received |

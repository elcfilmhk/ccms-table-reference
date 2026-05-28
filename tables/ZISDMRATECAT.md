# ZISDMRATECAT
**Description:** Custom Table for Statistics Report
**Total Fields:** 8
**Key Fields:** MANDT, RATE

## Programs Using This Table
- `zisdm0040`
- `zisdm0112`
- `zisdm0116`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RATE` | CHAR | 10 | 🔑 | Rate category |
| 3 | `RATEGROUP` | CHAR | 40 |  | Grouping of Rate Category |
| 4 | `SORTING` | NUMC | 2 |  | Rate category Sorting sequence |
| 5 | `EXCLUDE` | CHAR | 1 |  | Exclude rate category Indicator |
| 6 | `OUTLINE` | CHAR | 1 |  | Outline rate category Indicator |
| 7 | `CHINA` | CHAR | 1 |  | China rate category indicator |
| 8 | `NONREV` | CHAR | 1 |  | Nonrev rate category indicator |

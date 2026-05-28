# ZISCSESEAQDATA1
**Description:** Quarterly Submission of Summary of Total ES from Audit
**Total Fields:** 14
**Key Fields:** MANDT, AU_YEAR

## Programs Using This Table
- `ziscs0721`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AU_YEAR` | CHAR | 4 | 🔑 | Year |
| 3 | `Q1_VERIF` | INT4 | 10 |  | Fixed Values |
| 4 | `Q1_ES_ACH` | DEC | 25 |  | Achieved Energy Savings |
| 5 | `Q2_VERIF` | INT4 | 10 |  | Fixed Values |
| 6 | `Q2_ES_ACH` | DEC | 25 |  | Achieved Energy Savings |
| 7 | `Q3_VERIF` | INT4 | 10 |  | Fixed Values |
| 8 | `Q3_ES_ACH` | DEC | 25 |  | Achieved Energy Savings |
| 9 | `Q4_VERIF` | INT4 | 10 |  | Fixed Values |
| 10 | `Q4_ES_ACH` | DEC | 25 |  | Achieved Energy Savings |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

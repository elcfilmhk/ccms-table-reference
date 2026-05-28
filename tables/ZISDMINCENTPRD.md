# ZISDMINCENTPRD
**Description:** Incentive Period
**Total Fields:** 5
**Key Fields:** MANDT, TPLNR, INCENT_PERIOD

## Programs Using This Table
- `zisdm0218`
- `zisdm0221`
- `zisdm0222`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TPLNR` | CHAR | 30 | 🔑 | Functional Location |
| 3 | `INCENT_PERIOD` | NUMC | 2 | 🔑 | Incentive Period |
| 4 | `INCENT_STARTDATE` | DATS | 8 |  | Start Date |
| 5 | `INCENT_ENDDATE` | DATS | 8 |  | End Date |

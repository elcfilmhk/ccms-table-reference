# ZISFIBW_AGINGDET
**Description:** BW Extractor Table for Ageing Details
**Total Fields:** 17
**Key Fields:** MANDT, RUNDT, TARIFF, TARIFTYP, VKONT

## Programs Using This Table
- `zisfi0116`
- `zisfi0116_test`
- `zisfi0116_test2`
- `zisfi0116_test3`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `TARIFF` | CHAR | 22 | 🔑 | Tariff |
| 4 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `NOTDUE` | CURR | 13 |  | Not Due |
| 7 | `OVERDUE_1` | CURR | 13 |  | Over Due 1 - 30 days |
| 8 | `OVERDUE_2` | CURR | 13 |  | Over Due 31 - 60 days |
| 9 | `OVERDUE_3` | CURR | 13 |  | Over Due 61 - 90 days |
| 10 | `OVERDUE_4` | CURR | 13 |  | Over Due >90 days |
| 11 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
| 12 | `DUNNING_SCORE` | NUMC | 4 |  | Dunning Score |
| 13 | `DEPOSIT_HELD` | CURR | 13 |  | Deposit Held |
| 14 | `LIVEACC_IND` | CHAR | 1 |  | Live Account Indicator |
| 15 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `ERZET` | TIMS | 6 |  | Entry time |

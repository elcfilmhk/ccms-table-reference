# ZISDMADRCUSTRECA
**Description:** ADR Event customer reference CA
**Total Fields:** 4
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO

## Programs Using This Table
- `zisdm0309`
- `zisdm0356`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0274`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `REFCA` | CHAR | 12 |  | Contract Account Number |

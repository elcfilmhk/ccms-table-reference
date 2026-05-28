# ZISDMOCMRGROUP
**Description:** OC MR Group Mapping Table
**Total Fields:** 6
**Key Fields:** MANDT, OC, MR_GROUP

## Programs Using This Table
- `zisdh0021`
- `zisdh0022`
- `zisdh0023`
- `zisdh0024`
- `zisdh0026`
- `zisdm0025`
- `zisdm0040`
- `zisdm0151`
- `zisdm0158`
- `zisdm0159`
- `zisdm0192`
- `zisdm0211`
- `zisdm0233`
- `zisdm0248`
- `zisdm0249`
- `zisdm0252`
- `zisdm0253`
- `zisdm0254`
- `zisdm0259`
- `zisdm0260`
- `zisdm0261`
- `zisdm0263`
- `zisdm0271`
- `zisdm0350`
- `zisdm0407`
- `zisdm0409`
- `zisdm0411`
- `zisdm0412`
- `zisdm0420`
- `zismd0002`
- `zismd0029`
- `zrca_in_service`
- `zrca_in_service_lte`
- `zrdm_dr_rep`
- `zrdm_mr_rep`
- `zrdm_us_rep`
- `zrdm_wd_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OC` | CHAR | 3 | 🔑 | Operation Centre |
| 3 | `MR_GROUP` | CHAR | 2 | 🔑 | Meter Reading Group ( = MRU+2(2) ) |
| 4 | `ARBPL` | CHAR | 8 |  | Work Center |
| 5 | `ARBPL_CONV` | CHAR | 5 |  | Work centre conversion |
| 6 | `REGION` | CHAR | 10 |  | Region |

# ZISCSRESOURCES
**Description:** RE Source Information
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `ziscseec_re_con_appl==========ft`
- `ziscseec_recon_submit_recon_foft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RE_SOURCE` | CHAR | 2 |  | RE Source |
| 2 | `APP_TYPE` | CHAR | 2 |  | Application Type |
| 3 | `INST_LOC` | CHAR | 100 |  | RE System Location Name |
| 4 | `INST_TYP_ROOF` | CHAR | 1 |  | Room Installation Flag |
| 5 | `INST_TYP_POD` | CHAR | 1 |  | Podium Installation |
| 6 | `INST_TYP_LAND` | CHAR | 1 |  | Land Installation |
| 7 | `INST_TYP_OTH_FLAG` | CHAR | 1 |  | Others flag |
| 8 | `INST_TYP_OTH` | CHAR | 50 |  | Others Installation |
| 9 | `EXP_COMP_DAT` | DATS | 8 |  | Date of Last Change |
| 10 | `APP_CAP` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 11 | `TOT_GEN_CAP` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 12 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 13 | `ELEC_OUTPUT` | CHAR | 1 |  | Electricity Output(in phase) |

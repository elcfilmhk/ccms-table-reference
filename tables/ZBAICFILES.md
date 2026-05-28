# ZBAICFILES
**Description:** Interface control - physical files for interface run
**Total Fields:** 6
**Key Fields:** MANDT, SYSID, REPID, FUNCT, DATASETS

## Programs Using This Table
- `z_interface_get_filename======ft`
- `zbaice001`
- `zisbi0062`
- `zisbi0062_1`
- `zisbi0062_1t`
- `zisbi0071`
- `zisbi0071_tmp`
- `zisbi0094`
- `zisbi0110`
- `zisca0001`
- `ziscs0005`
- `ziscs0015`
- `ziscs0049`
- `ziscs0083`
- `zisdm0309`
- `zisdm0349`
- `zisfi0083`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0083_2`
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 4 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 5 | `DATASETS` | NUMC | 2 | 🔑 | Interface control: Number of inbound files for an interface |
| 6 | `PHYS_FILE` | CHAR | 255 |  | Interface control - Physical File Name |

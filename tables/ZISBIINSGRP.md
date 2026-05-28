# ZISBIINSGRP
**Description:** Primary Installations for Installation Group
**Total Fields:** 7
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zisbiinsgrp_tab_maintain`
- `zisdm0329`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `INST_NOT_APL_FOR_MIG` | CHAR | 1 |  | Not applicable for Migration |
| 4 | `REG_REL_TO_INSTGRP` | CHAR | 1 |  | Register Relationship to Inst Grp |
| 5 | `CUST_BILLDATE_MIG` | CHAR | 1 |  | Customer Bill Date Migration |
| 6 | `MIGRATION_DATE` | DATS | 8 |  | Migration Date |
| 7 | `POSTPROCESSED` | CHAR | 1 |  | Post processed flag |

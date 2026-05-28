# ZBARFCPARM
**Description:** Definitions for RFC Connections (Customized)
**Total Fields:** 4
**Key Fields:** MANDT, SYSID

## Programs Using This Table
- `ziscrm_patch_isu_ba_guid`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `RFCDEST_01` | CHAR | 32 |  | Logical destination (specified in function call) |
| 4 | `RFCDEST_02` | CHAR | 32 |  | Logical destination (specified in function call) |

# ZISFIRCR973
**Description:** Mapping table between position and branch
**Total Fields:** 6
**Key Fields:** MANDT, PLANS, PLSTX

## Programs Using This Table
- `ziscs0061`
- `zisfi0028`
- `zisfi0052`
- `zisfi0053`
- `zisfi0056`
- `zisfi0070`
- `zisfi0098`
- `zisfi0203`
- `zisfi0204`
- `zisfi0205`
- `zisfi0207`
- `zisfi0217`
- `zisfi0223`
- `zisfi0229`
- `zisfi0243_m`
- `zisfi0340`
- `zisfi0341`
- `zisfi0345`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PLANS` | NUMC | 8 | 🔑 | Position |
| 3 | `PLSTX` | CHAR | 40 | 🔑 | Object Name |
| 4 | `BRANCH` | CHAR | 6 |  | Type of branch (CTS, CSC, or BCC) |
| 5 | `SECTION_TYPE` | CHAR | 6 |  | Section Type |
| 6 | `TEAM` | CHAR | 6 |  | Team |

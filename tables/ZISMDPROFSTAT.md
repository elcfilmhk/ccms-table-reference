# ZISMDPROFSTAT
**Description:** Mapping of Load Profile Status from CCMS to MDMS
**Total Fields:** 5
**Key Fields:** MANDT, CCMS_STATUS

## Programs Using This Table
- `zismd0012`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CCMS_STATUS` | CHAR | 5 | 🔑 | Object status |
| 3 | `MDMS_STATUS1` | CHAR | 30 |  | MDMS Load Profile Status 1 |
| 4 | `MDMS_STATUS2` | CHAR | 30 |  | MDMS Load Profile Status 2 |
| 5 | `MDMS_STATUS3` | CHAR | 30 |  | MDMS Load Profile Status 3 |

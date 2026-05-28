# ZSENSITIVE_TCODE
**Description:** Sensitive TCode for CORS
**Total Fields:** 11
**Key Fields:** MANDT, SYS, TCODE, AGR_NAME

## Programs Using This Table
- `zisfi0330`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYS` | CHAR | 10 | 🔑 | System |
| 3 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 4 | `AGR_NAME` | CHAR | 30 | 🔑 | Composite role |
| 5 | `TCODE_TEXT` | CHAR | 36 |  | Transaction text |
| 6 | `TXN_INDICATOR` | CHAR | 5 |  | Transaction Indicator |
| 7 | `REMARK` | CHAR | 100 |  | Remark |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

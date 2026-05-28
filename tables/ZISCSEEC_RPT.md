# ZISCSEEC_RPT
**Description:** EE&C report instances
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, REPORT_TY, ISSUE_NO

## Programs Using This Table
- `ziscs0390_eec`
- `ziscs0391_eec`
- `ziscs0397_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REPORT_TY` | CHAR | 20 | 🔑 | Report Type |
| 4 | `ISSUE_NO` | CHAR | 20 | 🔑 | Report Issue No |
| 5 | `REPORT_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `REPORT_PERIOD_START` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `REPORT_PERIOD_END` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |

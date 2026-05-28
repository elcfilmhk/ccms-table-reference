# ZISFI_GOVT_DUN
**Description:** Dunning suppressed by government subsidy
**Total Fields:** 12
**Key Fields:** MANDT, LAUFD, VKONT, LAUFI

## Programs Using This Table
- `zisfi0186`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LAUFD` | DATS | 8 | 🔑 | Date ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `LAUFI` | CHAR | 6 | 🔑 | Additional Identification Characteristic |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 7 | `MBETM` | CURR | 13 |  | Dunned amount in transaction currency |
| 8 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 11 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 12 | `XVORL` | CHAR | 1 |  | Indicator: Only Proposal Run? |

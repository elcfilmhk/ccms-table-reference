# ZISDMAMRODLD
**Description:** Custom table to capture aperiodic MRO
**Total Fields:** 12
**Key Fields:** MANDT, ABLBELNR, ABLESGR

## Programs Using This Table
- `zisdh0009`
- `zisdm0335`
- `zisdm0336`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 4 | `ZRUNDATE` | DATS | 8 |  | Batch Run Date |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `ZDISPLAY` | CHAR | 8 |  | Display Flag |
| 7 | `GERNR` | CHAR | 18 |  | Meter Number |
| 8 | `E_ZWNUMMER` | NUMC | 3 |  | Register Number |
| 9 | `AEDAT` | DATS | 8 |  | Cancellation / Completion Date |
| 10 | `AENAM` | CHAR | 12 |  | Cancelled / Completed by |
| 11 | `ZFOLLWUPACTION` | CHAR | 132 |  | Follow-up Action |
| 12 | `AD_STRSPP2` | CHAR | 128 |  | Location |

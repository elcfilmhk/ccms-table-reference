# ZISEDEXPMSG_EXT
**Description:** EDM - Export Message table
**Total Fields:** 9
**Key Fields:** MANDT, RUNID, JOBNAME, ERROR_NO, TIMESTAMP

## Programs Using This Table
- `zedm_delta_housekeeping`
- `zedm_delta_housekeeping_sub`
- `zedm_ext_30int_dynamic`
- `zedm_ext_30int_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNID` | NUMC | 14 | 🔑 | Run ID for Profile Import Interface |
| 3 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 4 | `ERROR_NO` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 5 | `TIMESTAMP` | DEC | 15 | 🔑 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 6 | `CODE` | CHAR | 4 |  | EDM Message Code |
| 7 | `DATUM` | DATS | 8 |  | Field of type DATS |
| 8 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 9 | `MESSAGE` | CHAR | 255 |  | Text, 255 Characters |

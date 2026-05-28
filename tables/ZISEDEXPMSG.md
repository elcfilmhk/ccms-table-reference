# ZISEDEXPMSG
**Description:** EDM - Export Message table
**Total Fields:** 9
**Key Fields:** MANDT, RUNID, JOBNAME, ERROR_NO

## Programs Using This Table
- `zedm_delta_housekeeping_sub`
- `zedm_ext_30int_sub`
- `zised0016`
- `zised0023`
- `zised0025`
- `zised0053`
- `zised0054`
- `zised0055`
- `zised0065`
- `zised0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNID` | NUMC | 14 | 🔑 | Run ID for Profile Import Interface |
| 3 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 4 | `ERROR_NO` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 5 | `CODE` | CHAR | 4 |  | EDM Message Code |
| 6 | `DATUM` | DATS | 8 |  | Field of type DATS |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 9 | `MESSAGE` | CHAR | 255 |  | Text, 255 Characters |

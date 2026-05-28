# ZISCS_NGO_LOG
**Description:** Table for NGO Login Status Details
**Total Fields:** 6
**Key Fields:** MANDT, UCODE, REC_ID

## Programs Using This Table
- `ziscs0812`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UCODE` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 3 | `REC_ID` | NUMC | 8 | 🔑 | Record ID |
| 4 | `LOGDAT` | DATS | 8 |  | Date on which the object was created |
| 5 | `LOGTIM` | TIMS | 6 |  | Time at which the object was created |
| 6 | `LOGSTATUS` | CHAR | 1 |  | Login Status |

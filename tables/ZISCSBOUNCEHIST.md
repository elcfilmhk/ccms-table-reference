# ZISCSBOUNCEHIST
**Description:** Green Bill Email Bounced Back History
**Total Fields:** 6
**Key Fields:** MANDT, CTR_ACC_ID, ERDAT, ERZET, EMAIL

## Programs Using This Table
- `ziscs0004`
- `ziscs0288`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 5 | `EMAIL` | CHAR | 50 | 🔑 | Correspondence email |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

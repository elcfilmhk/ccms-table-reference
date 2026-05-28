# ZISDMRRECS
**Description:** Custom table to handle R Records of Meter Reading Upload
**Total Fields:** 12
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0143`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `REGCODE` | CHAR | 2 |  | Register Code |
| 7 | `READING` | CHAR | 10 |  | Reading |
| 8 | `REENTRY` | CHAR | 2 |  | Reentry count |
| 9 | `VALIDATIONCODE` | CHAR | 1 |  | Validation Code |
| 10 | `VALATTEMPT` | NUMC | 2 |  | Validation Attempt |
| 11 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 12 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |

# ZISCS_3LVAUTH_H
**Description:** 3 Level Authentication History
**Total Fields:** 13
**Key Fields:** MANDT, TIMESTAMP, UNIQUE_ID, CONTRACT_ACCOUNT

## Programs Using This Table
- `ziscs_3lv_auth_log`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TIMESTAMP` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `UNIQUE_ID` | CHAR | 32 | 🔑 | GUid of 32 characters |
| 4 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `CHANNEL` | CHAR | 1 |  | Channel |
| 6 | `AUTH_CODE` | CHAR | 12 |  | 3rd Level Authentication |
| 7 | `AUTH_ANS` | CHAR | 100 |  | Correct Answer |
| 8 | `INPUT_ANS` | CHAR | 100 |  | Input Answer |
| 9 | `OUTCOME` | CHAR | 1 |  | Result |
| 10 | `ATTEMPT_CNT` | NUMC | 2 |  | Attempt Count |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `ERZET` | TIMS | 6 |  | Entry time |

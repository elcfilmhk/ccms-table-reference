# ZISCS_MULTI_CA
**Description:** Account Association Management
**Total Fields:** 11
**Key Fields:** MANDT, ZPRIMARY_CA, ZSECONDARY_CA

## Programs Using This Table
- `ziscs0719`
- `ztest_auth_code_2`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZPRIMARY_CA` | CHAR | 12 | 🔑 | Primary CA |
| 3 | `ZSECONDARY_CA` | CHAR | 12 | 🔑 | Secondary CA |
| 4 | `ZDISPLAY_NAME` | CHAR | 80 |  | Display Name |
| 5 | `ZAUTH_CODE` | CHAR | 10 |  | Authentication code |
| 6 | `ZAUTH_IND` | CHAR | 1 |  | Authentication indicator |
| 7 | `ZDELINK` | CHAR | 1 |  | Delink indicator |
| 8 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 9 | `CREATED_TMST` | CHAR | 14 |  | Created Datetime |
| 10 | `MODIFIED_BY` | CHAR | 12 |  | Changed By |
| 11 | `MODIFIED_TMST` | CHAR | 14 |  | Changed Datetime |

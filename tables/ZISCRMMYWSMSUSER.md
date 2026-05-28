# ZISCRMMYWSMSUSER
**Description:** CRM My Workspace User Master
**Total Fields:** 33
**Key Fields:** MANDT, USERID

## Programs Using This Table
- `z_bapi_myws_em_user_info======ft`
- `ziscrm0009`
- `ziscrm0010`
- `ziscrm0012`
- `ziscrm0022`
- `ziscrm0031`
- `zisem_mol_highest_ca`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `USERID` | CHAR | 50 | 🔑 | Web Login ID |
| 3 | `SUPERID` | CHAR | 1 |  | Admin ID Indicator |
| 4 | `SURNAME` | CHAR | 20 |  | Surname |
| 5 | `NAME` | CHAR | 30 |  | Name |
| 6 | `SURNAME_C` | CHAR | 20 |  | Surname (Chinese) |
| 7 | `NAME_C` | CHAR | 30 |  | Name (Chinese) |
| 8 | `EMAIL` | CHAR | 50 |  | Email Address |
| 9 | `TITLE_P` | CHAR | 4 |  | Personal Title(Mr./Mrs/Ms.) |
| 10 | `TITLE_C` | CHAR | 40 |  | Job Title |
| 11 | `TEL` | CHAR | 30 |  | Contact tel |
| 12 | `LOGINTS` | CHAR | 14 |  | Last login timestamp |
| 13 | `PASSWD` | CHAR | 32 |  | User Password |
| 14 | `PASSWD_HINT` | CHAR | 100 |  | User Password Hint |
| 15 | `STATUS` | CHAR | 2 |  | Status |
| 16 | `LOGIN_FC` | INT1 | 3 |  | Failed login count |
| 17 | `LOGIN_FTS` | CHAR | 14 |  | Failed login timestamp |
| 18 | `ERNAM` | CHAR | 12 |  | Created By |
| 19 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 20 | `CHUSER` | CHAR | 12 |  | Changed by |
| 21 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 22 | `STAFFID` | CHAR | 12 |  | Staff ID |
| 23 | `LANG` | CHAR | 1 |  | Language |
| 24 | `CRT_EMAIL` | CHAR | 1 |  | Flag for new created email sent |
| 25 | `GEN_PWD` | CHAR | 1 |  | Flag for system generate password |
| 26 | `ROLE` | CHAR | 1 |  | Role |
| 27 | `USERID_D` | CHAR | 50 |  | Web Login ID (Display for user) |
| 28 | `TOKEN` | CHAR | 128 |  | Token |
| 29 | `TOKEN_EXPIRY` | DATS | 8 |  | Token expiry date |
| 30 | `TOKEN_CA` | CHAR | 12 |  | CA for token validation |
| 31 | `HIGHEST_CA` | CHAR | 12 |  | HIGHEST CA |
| 32 | `DEFAULT_CA` | CHAR | 12 |  | DEFAULT_CA |
| 33 | `DEFAULT_ME` | CHAR | 18 |  | DEFAULT_ME |

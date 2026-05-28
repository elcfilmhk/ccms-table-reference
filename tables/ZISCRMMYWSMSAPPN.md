# ZISCRMMYWSMSAPPN
**Description:** CRM My Workspace Application Master
**Total Fields:** 30
**Key Fields:** MANDT, SCHEME_NO, SUB_NO

## Programs Using This Table
- `ziscrm0010`
- `ziscrm0012`
- `ziscrm0014`
- `ziscrm0015`
- `ziscrm0015a`
- `ziscrm0017`
- `ziscrm0017a`
- `ziscrm0018`
- `ziscrm0018a`
- `ziscrm0020`
- `ziscrm0021`
- `ziscrm0031`
- `ziscrm0032`
- `ziscs0239`
- `ziscs0359`
- `zisem0003`
- `zisem0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME_NO` | CHAR | 12 | 🔑 | Scheme number |
| 3 | `SUB_NO` | CHAR | 12 | 🔑 | Subscription number |
| 4 | `APPDATE` | DATS | 8 |  | Application date |
| 5 | `VKONT_P` | CHAR | 12 |  | Virtual Contract Account for MYWS |
| 6 | `CP_NAME` | CHAR | 30 |  | Contact person name |
| 7 | `CP_TEL` | CHAR | 30 |  | Contact tel |
| 8 | `CP_FAX` | CHAR | 30 |  | Contact fax |
| 9 | `TITLE_C` | CHAR | 40 |  | Job Title |
| 10 | `PAID` | CHAR | 1 |  | Flag for paid service |
| 11 | `REMARK` | CHAR | 60 |  | Remark |
| 12 | `STATUS` | CHAR | 2 |  | Status |
| 13 | `ERNAM` | CHAR | 12 |  | Created By |
| 14 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 15 | `CHUSER` | CHAR | 12 |  | Changed by |
| 16 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 17 | `RESPONSIBLE` | CHAR | 10 |  | Responsible AM, BP number |
| 18 | `APPROVER_1` | CHAR | 40 |  | First Approver |
| 19 | `APPROVER_2` | CHAR | 40 |  | Second Approver |
| 20 | `BANK` | CHAR | 100 |  | Bank Name |
| 21 | `CHEQUE` | CHAR | 30 |  | Cheque |
| 22 | `PAYDATE` | DATS | 8 |  | Payment Date |
| 23 | `LANG` | CHAR | 2 |  | Language |
| 24 | `EMAIL` | CHAR | 50 |  | Email address |
| 25 | `PAYAMT` | CURR | 13 |  | Total payment amount |
| 26 | `APPDAT` | DATS | 8 |  | Approval date |
| 27 | `GRAND_TOTAL` | CURR | 13 |  | Amount |
| 28 | `BSTAT_DUEDATE` | DATS | 8 |  | Billing statement due date |
| 29 | `EMAIL_TO_BCC` | CHAR | 1 |  | Email to BCC |
| 30 | `REFUND_AMT` | CURR | 13 |  | Amount |

# ZISCS_EEC_EML_TRK_EV_SEARCH_RS
**Description:** Output Structure of ZISCS_EML_TRK_EV_SEARCH
**Total Fields:** 19
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `ziscs0714`
- `ziscs_eml_trk_ev_search=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EVNT_DT` | CHAR | 14 |  | Email Event Datetime |
| 2 | `EVNT_TYPE` | CHAR | 50 |  | Email Type for Email Tracking Platform |
| 3 | `RCPT_EML_ADDR` | CHAR | 80 |  | Single Email Recipient Email Address |
| 4 | `REQ_DT` | CHAR | 14 |  | Request Email Datetime |
| 5 | `EML_GUID` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 6 | `EML_TYPE` | CHAR | 50 |  | Email Type for Email Tracking Platform |
| 7 | `BP` | CHAR | 10 |  | Business Partner Number |
| 8 | `CA` | CHAR | 12 |  | Contract Account Number |
| 9 | `SUBJECT` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 10 | `SENDER_NAME` | CHAR | 50 |  | Email Sender Name |
| 11 | `SENDER_EML_ADDR` | CHAR | 100 |  | Email Sender Address |
| 12 | `EMP_PROVIDER` | CHAR | 50 |  | Provider/Vendor of email event tracking |
| 13 | `PROFILE_NAME` | CHAR | 30 |  | Text (30 Characters) |
| 14 | `PRINTDOC` | CHAR | 12 |  | Number of print document |
| 15 | `DISP_CONT` | CHAR | 4 |  | Dispatch control for original customer |
| 16 | `ENV` | CHAR | 3 |  | Environment (PRD/QA) |
| 17 | `UNAME` | CHAR | 12 |  | User Name |
| 18 | `MODE` | CHAR | 1 |  | Mode (Preview/Real) |
| 19 | `RCPT_EML_TOKEN` | CHAR | 32 |  | Recipient Email Address Token |

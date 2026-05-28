# ZISCSEML_TRK_HD
**Description:** Email Tracking Platform - Email instances
**Total Fields:** 11
**Key Fields:** MANDT, REQ_DT, EML_GUID

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | Request Email Datetime |
| 3 | `EML_GUID` | CHAR | 32 | 🔑 | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 4 | `EML_TYPE` | CHAR | 50 |  | Email Type for Email Tracking Platform |
| 5 | `BP` | CHAR | 10 |  | Business Partner Number |
| 6 | `CA` | CHAR | 12 |  | Contract Account Number |
| 7 | `SUBJECT` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 8 | `SENDER_NAME` | CHAR | 50 |  | Email Sender Name |
| 9 | `SENDER_EML_ADDR` | CHAR | 100 |  | Email Sender Address |
| 10 | `EMP_PROVIDER` | CHAR | 50 |  | Provider/Vendor of email event tracking |
| 11 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |

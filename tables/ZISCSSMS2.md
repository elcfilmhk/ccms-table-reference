# ZISCSSMS2
**Description:** SMS Content Mapping
**Total Fields:** 7
**Key Fields:** MANDT, SMS_CAT, SMSTYPE, APP_TYPE, PARTNER_TYPE, LANGU

## Programs Using This Table
- `ziscs_sms02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SMS_CAT` | CHAR | 2 | 🔑 | SMS Category : MI - Move-in, MO - Move-out |
| 3 | `SMSTYPE` | CHAR | 2 | 🔑 | SMSType:RE-Reminder,AC-ApplicationCompletion,FM-ForceMoveOut |
| 4 | `APP_TYPE` | CHAR | 1 | 🔑 | Application Type (Applicant - 'T' / Authorized Rep - 'A') |
| 5 | `PARTNER_TYPE` | CHAR | 2 | 🔑 | Partner Type : BP - Business Partner, AR - Authorized Rep |
| 6 | `LANGU` | LANG | 1 | 🔑 | Language Key |
| 7 | `SMS_NAME` | CHAR | 70 |  | Name of the SMS content |

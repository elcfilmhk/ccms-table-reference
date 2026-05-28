# ZISCSSMS3
**Description:** SMS Dynmic Variables Mapping
**Total Fields:** 9
**Key Fields:** MANDT, SMS_CAT, SMS_TYPE, LANGU, DYNAMIC_VARI

## Programs Using This Table
- `ziscs0301`
- `ziscs_sms02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SMS_CAT` | CHAR | 2 | 🔑 | SMS Category : MI - Move-in, MO - Move-out |
| 3 | `SMS_TYPE` | CHAR | 2 | 🔑 | SMSType:RE-Reminder,AC-ApplicationCompletion,FM-ForceMoveOut |
| 4 | `LANGU` | LANG | 1 | 🔑 | Language Key |
| 5 | `DYNAMIC_VARI` | CHAR | 30 | 🔑 | Dynamic Variables |
| 6 | `FIELDVALUE` | CHAR | 30 |  | Field Name |
| 7 | `ALTERNATEVALUE` | CHAR | 30 |  | Field Name |
| 8 | `CONVEXIT` | CHAR | 30 |  | Name of Function Module |
| 9 | `FIXED_VALUE` | CHAR | 100 |  | Fixed Value |

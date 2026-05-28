# ZISMDOUTSPCHANL
**Description:** Service Point Channel Output file
**Total Fields:** 13
**Key Fields:** MANDT, ANLAGE, CHANNEL_NO

## Programs Using This Table
- `zismd0007`
- `zismd0008`
- `zismd0011`
- `zismd0023`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `CHANNEL_NO` | NUMC | 10 | 🔑 | Service Point Channel Number |
| 4 | `DESCRIPTION` | CHAR | 100 |  | Description of the service point channel |
| 5 | `SHORTCUT_CODE` | CHAR | 30 |  | Shortcut code for the register channel |
| 6 | `CHANNEL_TYPE` | CHAR | 10 |  | Channel type - Interval / Register |
| 7 | `EFF_START_DATE` | DATS | 8 |  | Service Point Link effective start date |
| 8 | `CHANNEL_SOURCE` | CHAR | 1 |  | Channel Source |
| 9 | `MSEH6` | CHAR | 6 |  | External Unit of Measurement in Technical Format (6-Char.) |
| 10 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |
| 11 | `VALIDSETID1` | CHAR | 50 |  | Validation Set ID 1 |
| 12 | `VALIDSETID2` | CHAR | 50 |  | Validation Set ID 2 |
| 13 | `VALIDSETID3` | CHAR | 50 |  | Validation Set ID 3 |

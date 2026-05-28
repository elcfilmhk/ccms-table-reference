# ZISCSEML_TRK_HD1
**Description:** Email Tracking Platform - Email instances misc. fields
**Total Fields:** 7
**Key Fields:** MANDT, REQ_DT, EML_GUID, VAR_NAME

## Programs Using This Table
- `zisbi0232`
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | Request Email Datetime |
| 3 | `EML_GUID` | CHAR | 32 | 🔑 | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 4 | `VAR_NAME` | CHAR | 100 | 🔑 | Name of variables in EE&C email template |
| 5 | `VAR_VALUE` | CHAR | 1000 |  | Case-sensitive Text of 1000 length |
| 6 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `DELETE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |

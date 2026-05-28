# ZCRM_MESSAGE_RETURN
**Description:** FI Messages
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zcrm_doc_change===============ft`
- `zfi_crm_fps_maxlimit==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MSGID` | CHAR | 20 |  | Message Class |
| 2 | `MSGTY` | CHAR | 1 |  | Message Type |
| 3 | `MSGNO` | NUMC | 3 |  | Message Number |
| 4 | `MSGV1` | CHAR | 50 |  | Message Variable |
| 5 | `MSGV2` | CHAR | 50 |  | Message Variable |
| 6 | `MSGV3` | CHAR | 50 |  | Message Variable |
| 7 | `MSGV4` | CHAR | 50 |  | Message Variable |
| 8 | `MESSAGE` | CHAR | 220 |  | Message Text |

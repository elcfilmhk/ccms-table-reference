# ZZFI_RET_MSG_STRUCT
**Description:** Structure of returned messages
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_defer_due_date=========ft`
- `z_bapi_defer_due_date_nolog===ft`
- `z_bapi_defer_due_date_ws======ft`
- `ziscs0370_pyl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MSG_TYPE` | CHAR | 1 |  | 'I'nfo; 'E'rror; 'W'arning |
| 2 | `MSG_CODE` | CHAR | 100 |  | Error Code (for catching by Program) |
| 3 | `MSG_TEXT` | CHAR | 3000 |  | Error Message (Human-Readable) |

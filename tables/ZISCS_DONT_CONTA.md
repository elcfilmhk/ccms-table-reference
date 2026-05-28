# ZISCS_DONT_CONTA
**Description:** DO NOT CONTACT List
**Total Fields:** 7
**Key Fields:** MANDT, CONTACT_DATA, CONTACT_TYPE, LIST_TYPE, CREATED_DT

## Programs Using This Table
- `ziscs0841`
- `ziscs_do_not_contact_maint`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTACT_DATA` | CHAR | 80 | 🔑 | Contact Number/Address for ZISCS_DONT_CONTA |
| 3 | `CONTACT_TYPE` | CHAR | 10 | 🔑 | Contact Type for ZISCS_DONT_CONTA |
| 4 | `LIST_TYPE` | CHAR | 10 | 🔑 | List Type for ZISCS_DONT_CONTA |
| 5 | `CREATED_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `REMARKS` | CHAR | 300 |  | Text length 300 |
| 7 | `CREATED_BY` | CHAR | 12 |  | User Name |

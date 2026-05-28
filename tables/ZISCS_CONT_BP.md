# ZISCS_CONT_BP
**Description:** Contacts ever used by BP
**Total Fields:** 8
**Key Fields:** MANDT, CONTACT_DATA, CONTACT_TYPE, GPART, VKONT

## Programs Using This Table
- `ziscs0841`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTACT_DATA` | CHAR | 80 | 🔑 | Contact Number/Address for ZISCS_DONT_CONTA |
| 3 | `CONTACT_TYPE` | CHAR | 10 | 🔑 | Contact Type for ZISCS_DONT_CONTA |
| 4 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `USE_LOCATION` | CHAR | 80 |  | Char 80 |
| 7 | `LAST_FOUND_DATE` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `CONTACT_DATA_LEN` | INT4 | 10 |  | Natural number |

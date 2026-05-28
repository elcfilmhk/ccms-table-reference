# ZUPD_ADRP
**Description:** ADRP name masking
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `ziscv08`
- `ziscv08nv`
- `ziscv08nv_test`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PERSNUMBER` | CHAR | 10 |  | Person number |
| 2 | `DATE_FROM` | DATS | 8 |  | Valid-from date - in current Release only 00010101 possible |
| 3 | `NATION` | CHAR | 1 |  | Version ID for International Addresses |
| 4 | `NAME_FIRST` | CHAR | 40 |  | First Name |
| 5 | `NAME_LAST` | CHAR | 40 |  | Last name |
| 6 | `NAME_TEXT` | CHAR | 80 |  | Full Name of Person |
| 7 | `MC_NAMEFIR` | CHAR | 25 |  | First Name in Uppercase for Search Help |
| 8 | `MC_NAMELAS` | CHAR | 25 |  | Last Name in Uppercase for Search Help |

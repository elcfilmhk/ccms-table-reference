# ZUPD_ADRC
**Description:** ADRC name masking
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `ziscv08`
- `ziscv08nv`
- `ziscv08nv_test`
- `ziscv09`
- `ziscv09nv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 2 | `DATE_FROM` | DATS | 8 |  | Valid-from date - in current Release only 00010101 possible |
| 3 | `NATION` | CHAR | 1 |  | Version ID for International Addresses |
| 4 | `NAME1` | CHAR | 40 |  | Name 1 |
| 5 | `NAME2` | CHAR | 40 |  | Name 2 |
| 6 | `NAME4` | CHAR | 40 |  | Name 4 |
| 7 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 8 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 9 | `ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 10 | `SORT1` | CHAR | 20 |  | Search Term 1 |
| 11 | `MC_NAME1` | CHAR | 25 |  | Name (Field NAME1) in Uppercase for Search Help |

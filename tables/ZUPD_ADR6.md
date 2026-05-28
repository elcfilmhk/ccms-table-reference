# ZUPD_ADR6
**Description:** ADR6 data masking
**Total Fields:** 6
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
| 2 | `PERSNUMBER` | CHAR | 10 |  | Person number |
| 3 | `DATE_FROM` | DATS | 8 |  | Valid-from date - in current Release only 00010101 possible |
| 4 | `CONSNUMBER` | NUMC | 3 |  | Sequence Number |
| 5 | `SMTP_ADDR` | CHAR | 241 |  | E-Mail Address |
| 6 | `SMTP_SRCH` | CHAR | 20 |  | E-Mail Address Search Field |

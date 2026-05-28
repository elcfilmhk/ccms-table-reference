# ZUPD_ADR2
**Description:** ADR2 data masking
**Total Fields:** 8
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
| 5 | `TEL_NUMBER` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 6 | `TEL_EXTENS` | CHAR | 10 |  | Telephone no.: Extension |
| 7 | `TELNR_LONG` | CHAR | 30 |  | Complete Number: Dialling Code+Number+Extension |
| 8 | `TELNR_CALL` | CHAR | 30 |  | Telephone number for determining caller |

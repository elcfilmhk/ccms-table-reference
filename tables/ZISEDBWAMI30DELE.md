# ZISEDBWAMI30DELE
**Description:** Temporary profile table
**Total Fields:** 8
**Key Fields:** MANDT, PROFILE

## Programs Using This Table
- `zedm_delta_housekeeping_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 3 | `SERNR` | CHAR | 18 |  | Serial Number |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 6 | `MASSBILL` | UNIT | 3 |  | Unit of measurement for meter reading |
| 7 | `DATEFROM` | DATS | 8 |  | From-Date |
| 8 | `DATETO` | DATS | 8 |  | To-Date |

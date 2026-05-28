# ZISDMCUSAC
**Description:** Custome table for LPIS (customer account  information)
**Total Fields:** 13
**Key Fields:** MANDT, VKONTO, GERNR

## Programs Using This Table
- `zisdm0059`
- `zisdm0060`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `VKBEZ` | CHAR | 40 |  | Character field of length 40 |
| 5 | `ZZTARIFTYP` | CHAR | 1 |  | Tariff Type (CISS) |
| 6 | `BRGEW` | CHAR | 7 |  | Character field, length 7 |
| 7 | `GROES` | CHAR | 32 |  | Size/dimensions |
| 8 | `METER_IND` | CHAR | 1 |  | Single-Character Flag |
| 9 | `EINBDAT` | CHAR | 10 |  | Character Field Length = 10 |
| 10 | `KWH` | CHAR | 8 |  | Character field, 8 characters long |
| 11 | `KVA` | CHAR | 8 |  | Character field, 8 characters long |
| 12 | `KWH_NRB` | CHAR | 1 |  | Single-Character Flag |
| 13 | `KVA_NRB` | CHAR | 1 |  | Single-Character Flag |

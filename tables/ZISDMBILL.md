# ZISDMBILL
**Description:** Custome table for LPIS (Billing information)
**Total Fields:** 19
**Key Fields:** MANDT, CON_ACCT, VKONTO, HAUS, VSTELLE, ADAT, EINZDAT, AUSZDAT, PREV_ADAT

## Programs Using This Table
- `zisdm0059`
- `zisdm0060`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CON_ACCT` | CHAR | 8 | 🔑 | Character field, 8 characters long |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `HAUS` | CHAR | 30 | 🔑 | 30 Characters |
| 5 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 6 | `ADAT` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 7 | `EINZDAT` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 8 | `AUSZDAT` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 9 | `PREV_ADAT` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 10 | `ZZTARIFTYP` | CHAR | 1 |  | Tariff Type (CISS) |
| 11 | `ZZSUBTRFTY` | CHAR | 1 |  | Sub Tariff Type (CISS) |
| 12 | `FIR_KTOKL` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 13 | `LAST_KTOKL` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 14 | `OFF_KVA` | CHAR | 9 |  | Character field of 9 digits |
| 15 | `ON_KVA` | CHAR | 9 |  | Character field of 9 digits |
| 16 | `MAX_KVA` | CHAR | 9 |  | Character field of 9 digits |
| 17 | `OFF_KWH` | CHAR | 9 |  | Character field of 9 digits |
| 18 | `ON_KWH` | CHAR | 9 |  | Character field of 9 digits |
| 19 | `MAX_KWH` | CHAR | 9 |  | Character field of 9 digits |

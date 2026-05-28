# ZISDMDEVLC
**Description:** Device Level Consumption Table
**Total Fields:** 11
**Key Fields:** MANDT, VSTELLE, GERNR, ZWART, ZWTYP, MASSREAD, ADAT

## Programs Using This Table
- `zbacbdb01`
- `zbacbdb02`
- `zbacbdb03`
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0029`
- `zisdm0039`
- `zisdm0056`
- `zisdm0059`
- `zisdm0060`
- `zisdm0075`
- `zisdm0090`
- `zisdm0091`
- `zisdm0098`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ZWART` | CHAR | 2 | 🔑 | Register type |
| 5 | `ZWTYP` | NUMC | 2 | 🔑 | Register category |
| 6 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 7 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 8 | `READINGRESULT` | CHAR | 32 |  | Meter reading recorded |
| 9 | `ZZCONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 10 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 11 | `MRTYPE` | CHAR | 1 |  | MR Type - CISS Meter Read type field |

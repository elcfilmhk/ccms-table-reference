# ZISCSCHDOC
**Description:** Contract Change Doc - Future Move-in / Move-out - CSPS
**Total Fields:** 11
**Key Fields:** MANDT, VERTRAG, EFFDAT

## Programs Using This Table
- `ziscs0073`
- `ziscs0079`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `EFFDAT` | DATS | 8 | 🔑 | Effective Date |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `OPCODE` | CHAR | 1 |  | Operation Code |
| 6 | `VSTELLE` | CHAR | 10 |  | Premise |
| 7 | `ANLAGE` | CHAR | 10 |  | Installation |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `REVERSED` | CHAR | 1 |  | Single-Character Flag |
| 10 | `MULTIPLE` | CHAR | 1 |  | Single-Character Flag |
| 11 | `CHANGED_FUTURE` | CHAR | 1 |  | Single-Character Flag |

# ZISDMCUSTYP
**Description:** to represent the customer type
**Total Fields:** 7
**Key Fields:** MANDT, SPARTE, AKLASSE, TARIFTYP

## Programs Using This Table
- `zisdm0023`
- `zisdm0036`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SPARTE` | CHAR | 2 | 🔑 | Division |
| 3 | `AKLASSE` | CHAR | 4 | 🔑 | Billing class |
| 4 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 5 | `TTYPBEZ` | CHAR | 40 |  | Text for Rate Category |
| 6 | `ZGROUP` | CHAR | 4 |  | Outsorting check group |
| 7 | `TARIFF` | CHAR | 10 |  | Billing Schema |

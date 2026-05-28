# ZISDMCONTR
**Description:** Contract Table
**Total Fields:** 6
**Key Fields:** MANDT, VKONTO, VERTRAG, VSTELLE, EINZDAT

## Programs Using This Table
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0021`
- `zisdm0029`
- `zisdm0039`
- `zisdm0057`
- `zisdm0058`
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
| 2 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 5 | `EINZDAT` | DATS | 8 | 🔑 | Move-In Date |
| 6 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |

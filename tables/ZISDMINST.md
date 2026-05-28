# ZISDMINST
**Description:** Installation Table
**Total Fields:** 5
**Key Fields:** MANDT, VSTELLE, GERNR, EINBDAT

## Programs Using This Table
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0039`
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
| 4 | `EINBDAT` | DATS | 8 | 🔑 | Installation date |
| 5 | `AUSBDAT` | DATS | 8 |  | Device removal date |

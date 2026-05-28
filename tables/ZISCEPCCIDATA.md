# ZISCEPCCIDATA
**Description:** CEP: CCI file data
**Total Fields:** 9
**Key Fields:** MANDT, PARTNER, VSTELLE, CLASSIFIER

## Programs Using This Table
- `ziscs0345`
- `ziscs0353`
- `ziscs0354`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 4 | `CLASSIFIER` | CHAR | 30 | 🔑 | 30 Characters |
| 5 | `VALUE` | CHAR | 10 |  | Character Field Length = 10 |
| 6 | `START_DATE` | DATS | 8 |  | Field of type DATS |
| 7 | `END_DATE` | DATS | 8 |  | Field of type DATS |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `EXPORT_DATE` | DATS | 8 |  | Field of type DATS |

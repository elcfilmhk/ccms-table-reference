# ZISCSPC_ENER_BDG
**Description:** Table to store final output data for check bill badge object
**Total Fields:** 16
**Key Fields:** MANDT, OPBEL, VKONT, BELNR

## Programs Using This Table
- `ziscs0824`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 7 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 8 | `OLD_BELNR` | CHAR | 12 |  | Number of a billing document |
| 9 | `ADC_CURR_YEAR` | DEC | 16 |  | Entry value (installed value) for a device |
| 10 | `ADC_LAST_YEAR` | DEC | 16 |  | Entry value (installed value) for a device |
| 11 | `ENERGYSAVING` | DEC | 16 |  | Energy Changes (%) |
| 12 | `BADGE_INCENTIVE` | CHAR | 1 |  | General Flag |
| 13 | `TEXT` | CHAR | 255 |  | Char255 |
| 14 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 15 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 16 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |

# ZISCSEEC_BENLSBD
**Description:** Temp table for EE&C CA latest billing documents
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, VERTRAG

## Programs Using This Table
- `ziscs0387_eec`
- `ziscs0392_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 5 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 6 | `ENDABRPE` | DATS | 8 |  | End of billing period |

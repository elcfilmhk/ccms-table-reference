# ZISDMERCH_TMP
**Description:** Temporary table for ZISDM0241 to store billing doc data
**Total Fields:** 9
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zisdm0241`
- `zisdm0241_sub`
- `zisdm0241n`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 |  | Contract |
| 5 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 6 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 7 | `TARIFNR` | CHAR | 10 |  | Rate key |
| 8 | `PID` | NUMC | 5 |  | Process ID |
| 9 | `PROCESSED` | CHAR | 1 |  | Character Field Length 1 |

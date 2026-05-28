# ZISDMMRREC
**Description:** Custom table for Meter Reading data on record created date
**Total Fields:** 14
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0079`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `GERNR` | CHAR | 18 |  | Device |
| 6 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 7 | `ABLESGR` | CHAR | 2 |  | Meter reading reasons for single entry |
| 8 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 9 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 10 | `ATIM` | CHAR | 4 |  | Meter reading time (relevant to billing) |
| 11 | `ABLSTAT` | CHAR | 1 |  | Meter Reading Status |
| 12 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 13 | `ANLAGE` | CHAR | 10 |  | Installation |
| 14 | `TARIFTYP` | CHAR | 10 |  | Rate category |

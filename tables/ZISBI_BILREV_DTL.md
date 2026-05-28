# ZISBI_BILREV_DTL
**Description:** Bill Reversal Details
**Total Fields:** 20
**Key Fields:** MANDT, VKONT, ITEMNUMBER, ERDAT, ERZET, BELNRALT

## Programs Using This Table
- `zisbi0234`
- `zisbi_dsm_logreport`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ITEMNUMBER` | CHAR | 3 | 🔑 | Item Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 6 | `BELNRALT` | CHAR | 12 | 🔑 | Number of previous document |
| 7 | `REVDOC` | CHAR | 12 |  | Reversal print document number |
| 8 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 9 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 10 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 11 | `OPBEL` | CHAR | 12 |  | Number of print document |
| 12 | `VERTRAG` | CHAR | 10 |  | Contract |
| 13 | `ANLAGE` | CHAR | 10 |  | Installation |
| 14 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 15 | `AEDATP` | DATS | 8 |  | Date of Last Change |
| 16 | `AENAMP` | CHAR | 12 |  | Name of person who changed object |
| 17 | `MESSAGE1` | CHAR | 220 |  | Message Text |
| 18 | `MESSAGE2` | CHAR | 220 |  | Message Text |
| 19 | `MESSAGE3` | CHAR | 220 |  | Message Text |
| 20 | `MESSAGE4` | CHAR | 220 |  | Message Text |

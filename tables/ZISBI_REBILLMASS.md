# ZISBI_REBILLMASS
**Description:** Table to store status for reverse and rebill program
**Total Fields:** 14
**Key Fields:** MANDT, ANLAGE, VKONT, ERDAT, ERZEIT

## Programs Using This Table
- `zisbi0260`
- `zisbi0261`
- `zisbi0262`
- `zisbi0266`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 6 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 7 | `BATCHONLN` | CHAR | 1 |  | Batch or Online for rebill/reverse status |
| 8 | `APPRSTATUS` | CHAR | 1 |  | Approval Status |
| 9 | `COMPLFLAG` | CHAR | 1 |  | Completion Flag |
| 10 | `ERROR` | CHAR | 1 |  | Error |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `APNAM` | CHAR | 12 |  | Approved By |
| 13 | `APDAT` | DATS | 8 |  | Approval Date |
| 14 | `APZEIT` | TIMS | 6 |  | Approval Time |

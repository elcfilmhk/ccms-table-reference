# ZISBISIMDOC3
**Description:** Simulation document for leftout RBI25
**Total Fields:** 11
**Key Fields:** MANDT, PERIOD, VKONT, LFDNR

## Programs Using This Table
- `zisbi0061`
- `zisbi0062b`
- `zisbi0062c`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `LFDNR` | NUMC | 3 | 🔑 | Sequence Number (Internal Use Only) |
| 5 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `APDAT` | DATS | 8 |  | Date Approved |
| 9 | `APNAM` | CHAR | 12 |  | Approver Name |
| 10 | `DELDAT` | DATS | 8 |  | Deletion date |
| 11 | `DELNAM` | CHAR | 12 |  | Deleted by |

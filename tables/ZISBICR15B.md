# ZISBICR15B
**Description:** Temporary Data for Billing Adjustment Workflow
**Total Fields:** 7
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zbilldoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

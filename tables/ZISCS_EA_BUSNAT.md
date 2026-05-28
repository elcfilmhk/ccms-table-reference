# ZISCS_EA_BUSNAT
**Description:** Customer Business Nature
**Total Fields:** 8
**Key Fields:** MANDT, CUST_BUS_TYPE

## Programs Using This Table
- `ziscs0723`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CUST_BUS_TYPE` | CHAR | 3 | 🔑 | Customer Business Nature |
| 3 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 4 | `DESCRIPTION_CH` | CHAR | 100 |  | General Description |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

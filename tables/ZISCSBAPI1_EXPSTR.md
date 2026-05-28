# ZISCSBAPI1_EXPSTR
**Description:** Export structure for Eservice Header
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_retrieve_eservice_hdr==ft`
- `ziscs0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERVTYPE` | CHAR | 10 |  | Service Type |
| 2 | `CHANNEL` | CHAR | 10 |  | Channel |
| 3 | `STATUS` | CHAR | 1 |  | Status |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Create By |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Change By |

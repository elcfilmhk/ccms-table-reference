# ZISCS_MTRREAD_CA
**Description:** Autogrid Contract Account meter read extract
**Total Fields:** 10
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs_autogrid_ca`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CUST_TYPE` | CHAR | 2 |  | Customer Type |
| 4 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `ETIME` | TIMS | 6 |  | Time created |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `UTIME` | TIMS | 6 |  | Time changed |

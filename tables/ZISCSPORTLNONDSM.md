# ZISCSPORTLNONDSM
**Description:** Portal Access Validity for Non-DSM Customers
**Total Fields:** 10
**Key Fields:** MANDT, DSMPROGID, VKONT

## Programs Using This Table
- `ziscs0485`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DSMPROGID` | CHAR | 6 | 🔑 | DSM Program ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `NONDSMPORTDATE` | DATS | 8 |  | Non-DSM Portal End Date |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERZET` | TIMS | 6 |  | Entry time |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

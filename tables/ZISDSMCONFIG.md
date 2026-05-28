# ZISDSMCONFIG
**Description:** Global configuration values for AMI DSM Program
**Total Fields:** 12
**Key Fields:** MANDT, DSMPROGID

## Programs Using This Table
- `zisbi0234`
- `ziscs0480`
- `ziscs0713`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DSMPROGID` | CHAR | 6 | 🔑 | DSM Program ID |
| 3 | `DSMAB` | DATS | 8 |  | DSM Program Start Date |
| 4 | `DSMBIS` | DATS | 8 |  | DSM Program End Date |
| 5 | `AMIPORTLACESAB` | DATS | 8 |  | Non-DSM Portal Start Date |
| 6 | `AMIPORTLACESBIS` | DATS | 8 |  | Non-DSM Portal End Date |
| 7 | `AMIBLNGERSTDT` | DATS | 8 |  | Earliest date to Change the AMI Billing Method |
| 8 | `AMIBLCHGDAT` | DATS | 8 |  | AMI Bill Method Change Date |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

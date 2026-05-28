# ZISCSMCMS_EVIP
**Description:** VIP for Email channel
**Total Fields:** 9
**Key Fields:** MANDT, EMAIL_ADDRESS, TYPE

## Programs Using This Table
- `ziscs0375`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMAIL_ADDRESS` | CHAR | 50 | 🔑 | Email address |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Email Type |
| 4 | `VIP_PRIORITY` | CHAR | 3 |  | VIP priority |
| 5 | `STATUS` | CHAR | 1 |  | Status |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

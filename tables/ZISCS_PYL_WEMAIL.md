# ZISCS_PYL_WEMAIL
**Description:** Power Your Love Welcome Email
**Total Fields:** 11
**Key Fields:** MANDT, PYL_ID, VKONT

## Programs Using This Table
- `ziscs0369_pyl`
- `ziscs0401`
- `ziscs0402`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EMAIL` | CHAR | 100 |  | Email |
| 5 | `QR_CODE` | CHAR | 100 |  | Encrypted QR Code |
| 6 | `STATUS` | CHAR | 1 |  | Single-Character Flag |
| 7 | `SEND_DATE` | DATS | 8 |  | Date |
| 8 | `SEND_TIME` | TIMS | 6 |  | Time |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERZET` | TIMS | 6 |  | Entry time |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

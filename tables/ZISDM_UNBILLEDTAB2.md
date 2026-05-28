# ZISDM_UNBILLEDTAB2
**Description:** Structure for tab 2
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ANLAGE` | CHAR | 10 |  | Installation |
| 2 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 3 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 4 | `PORTION` | CHAR | 8 |  | Portion |
| 5 | `SERNR` | CHAR | 18 |  | Meter number |
| 6 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 7 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 8 | `PROFILE_DATE` | DATS | 8 |  | Profile Date |
| 9 | `PROFILE_TIME` | TIMS | 6 |  | Time |
| 10 | `PROFILE_VALUE` | DEC | 31 |  | Profile value at application level |
| 11 | `PROFILE_STATUS` | CHAR | 4 |  | Status of profile value in interface |

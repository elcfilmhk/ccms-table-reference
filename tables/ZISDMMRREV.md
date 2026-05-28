# ZISDMMRREV
**Description:** Custom table for MR on record reversal date
**Total Fields:** 26
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdh0009`
- `zisdh0022`
- `zisdm0100`
- `zisdm0100_1`
- `zisdm0336`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ABLESGR` | CHAR | 2 |  | Meter reading reasons for single entry |
| 4 | `ABLSTAT` | CHAR | 1 |  | Meter Reading Status |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 8 | `ANLAGE` | CHAR | 10 |  | Installation |
| 9 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 10 | `TYPE` | CHAR | 1 |  | Business Partner Category |
| 11 | `NAME_ORG1` | CHAR | 40 |  | Name 1 of organization |
| 12 | `NAME_ORG2` | CHAR | 40 |  | Name 2 of organization |
| 13 | `NAME_ORG3` | CHAR | 40 |  | Name 3 of organization |
| 14 | `NAME_ORG4` | CHAR | 40 |  | Name 4 of organization |
| 15 | `NAME_LAST` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 16 | `NAME_FIRST` | CHAR | 40 |  | First Name of Business Partner (Person) |
| 17 | `GERNR` | CHAR | 18 |  | Serial Number |
| 18 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 19 | `ZWNABR` | CHAR | 1 |  | Register not relevant to billing |
| 20 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 21 | `ADATTATS` | DATS | 8 |  | Actual meter reading date |
| 22 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 23 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 24 | `N_ZWSTAND` | DEC | 14 |  | Places After Decimal Point in the Meter Reading |
| 25 | `ZZOSMRO` | INT1 | 3 |  | Number of Outstanding MRO |
| 26 | `ZZREVMRDOC` | INT1 | 3 |  | Number of MR Result |

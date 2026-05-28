# ZISCSAPPSINFO
**Description:** Mobile billing and Payment Alert
**Total Fields:** 12
**Key Fields:** MANDT, ACCOUNTNUMBER

## Programs Using This Table
- `zisbi0160`
- `ziscs0718`
- `ziscs0720`
- `ziscs0732`
- `zisfi0347`
- `zrca_ssr_cust_extract`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACCOUNTNUMBER` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DEVICETOKEN` | CHAR | 256 |  | The push notification token of mobile device (Pass from App) |
| 4 | `DEVICETYPE` | CHAR | 1 |  | Device Type (iPhone or Android) |
| 5 | `LANG` | LANG | 1 |  | Language (The push notification message language) |
| 6 | `STATUS` | CHAR | 1 |  | Mobile billing status |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERZET` | TIMS | 6 |  | Entry time |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

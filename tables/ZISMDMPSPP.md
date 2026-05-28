# ZISMDMPSPP
**Description:** MDMS mapping for meter program and service point program
**Total Fields:** 10
**Key Fields:** MANDT, ZWGRUPPE, HERST, TYPBZ

## Programs Using This Table
- `zisdm0127`
- `zismd0030`
- `zismd0032`
- `zismd0033`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWGRUPPE` | CHAR | 8 | 🔑 | Register Group |
| 3 | `HERST` | CHAR | 30 | 🔑 | Manufacturer of asset |
| 4 | `TYPBZ` | CHAR | 20 | 🔑 | Manufacturer model number |
| 5 | `METERPROG` | CHAR | 20 |  | MDMS Meter Program |
| 6 | `SERVICEPTPROG` | CHAR | 20 |  | MDMS Service point program |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

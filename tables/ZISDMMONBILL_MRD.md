# ZISDMMONBILL_MRD
**Description:** MR document processed in monthly bill
**Total Fields:** 10
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0297_sub`
- `zisdm0298_sub`
- `zisdm0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `GERNR` | CHAR | 18 |  | Serial Number |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `ANLAGE` | CHAR | 10 |  | Installation |
| 6 | `MONTHLYBILL` | CHAR | 1 |  | Monthly bill |
| 7 | `INST_TYPE` | CHAR | 20 |  | Installation Type |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `ACTION` | CHAR | 10 |  | Monthly Bill Action |

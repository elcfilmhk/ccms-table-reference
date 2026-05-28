# ZISCSSMSREG
**Description:** SMS/FAX billing registration on Web
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, GPART, ERDAT, ERZEIT

## Programs Using This Table
- `z_isu_sample_z1905============ft`
- `zisbi0137`
- `ziscs0136`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `SMSFAXIND` | CHAR | 1 |  | SMS/Fax billing indicator |
| 8 | `PHONENO` | CHAR | 20 |  | SMS billing telephone number |
| 9 | `SEND` | CHAR | 1 |  | SMS/FAX confirmation letter send? |
| 10 | `ACTION` | CHAR | 1 |  | Action log |

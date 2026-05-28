# ZISCS_EEC_EO_HEA_PIE_OUT
**Description:** Output Structure for FM "ZISCSEEC_EO_HEA_PIE"
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `ziscseec_eo_hea_pie_ws========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Table to store EE&C HEA Piechart Slices |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `GROUPID` | CHAR | 20 |  | EE&C HEA Group ID |
| 4 | `SLICE_CAT` | CHAR | 20 |  | Slice Category |
| 5 | `SEQ` | INT4 | 10 |  | Natural number |
| 6 | `LABEL_EN` | CHAR | 50 |  | Text Field |
| 7 | `LABEL_ZF` | CHAR | 50 |  | Text Field |
| 8 | `DESC_EN` | CHAR | 200 |  | Text for translation |
| 9 | `DESC_ZF` | CHAR | 200 |  | Text for translation |
| 10 | `WEIGHT` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |

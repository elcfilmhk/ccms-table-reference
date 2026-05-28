# ZISDH_DEV_MST_DTL
**Description:** Device Master Details
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `zisdh0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 2 | `LOGIKNR` | NUMC | 18 |  | Logical device number |
| 3 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 4 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 5 | `DEVLOC` | CHAR | 30 |  | Device Location |
| 6 | `EQUNR_OBJ` | CHAR | 50 |  | Key of object to be classified |
| 7 | `TIDNR` | CHAR | 25 |  | Technical identification number |
| 8 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 9 | `LOGIKZW` | NUMC | 18 |  | Logical register number |
| 10 | `STORTZUS` | CHAR | 30 |  | Addition to device location |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 13 | `SEQNO` | NUMC | 8 |  | Route sequence number for each record |

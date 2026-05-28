# ZISDMIHD
**Description:** IHD associated with the device
**Total Fields:** 11
**Key Fields:** MANDT, SERNR, AB

## Programs Using This Table
- `zisdm0277`
- `zisdm0280`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 4 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 5 | `IHD_SN` | CHAR | 50 |  | IHD Serial Number |
| 6 | `IHD_MAC_ADDR` | CHAR | 16 |  | IHD Mac address |
| 7 | `IHD_INSTALL_CODE` | CHAR | 20 |  | IHD Install code |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

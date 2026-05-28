# ZISDMIHDLOG
**Description:** IHD associated with the device log
**Total Fields:** 15
**Key Fields:** MANDT, SERNR, AB, ACTION, UDATE, UTIME

## Programs Using This Table
- `zisdm0277`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 4 | `ACTION` | CHAR | 10 | 🔑 | Action |
| 5 | `UDATE` | DATS | 8 | 🔑 | Creation date of the change document |
| 6 | `UTIME` | TIMS | 6 | 🔑 | Time changed |
| 7 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 8 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 9 | `IHD_SN` | CHAR | 50 |  | IHD Serial Number |
| 10 | `IHD_MAC_ADDR` | CHAR | 16 |  | IHD Mac address |
| 11 | `IHD_INSTALL_CODE` | CHAR | 20 |  | IHD Install code |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

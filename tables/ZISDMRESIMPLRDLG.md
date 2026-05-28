# ZISDMRESIMPLRDLG
**Description:** Re-estimate Round clock implausible reading log
**Total Fields:** 8
**Key Fields:** MANDT, ABLBELNR, ERDAT, AEDAT

## Programs Using This Table
- `zisdm0317`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `AEDAT` | DATS | 8 | 🔑 | Date of Last Change |
| 5 | `CONTRDRDG` | DEC | 31 |  | Billing quantity for internal billing format |
| 6 | `GERNR` | CHAR | 18 |  | Serial Number |
| 7 | `CREATEDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `CREATETIME` | TIMS | 6 |  | Field of type TIMS |

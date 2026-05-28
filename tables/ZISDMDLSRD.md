# ZISDMDLSRD
**Description:** Downloaded Special Meter Reading Request table
**Total Fields:** 8
**Key Fields:** MANDT, ZMRDOCID

## Programs Using This Table
- `zisdm0025`
- `zisdm0027`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZMRDOCID` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ZGERNR` | CHAR | 18 |  | Device |
| 4 | `ZDOWNLOAD_DATE` | DATS | 8 |  | Date of download |
| 5 | `ZRDGTYPE` | CHAR | 1 |  | The Meter Reading Type |
| 6 | `ZTRANSFER_DATE` | DATS | 8 |  | Date when aperiodic read was transfered to Route Management |
| 7 | `ZDOWNLOADED` | CHAR | 1 |  | Display field - download was carried out |
| 8 | `ZORDER` | CHAR | 12 |  | Order Number |

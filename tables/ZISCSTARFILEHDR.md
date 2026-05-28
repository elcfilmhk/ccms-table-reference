# ZISCSTARFILEHDR
**Description:** CEP: Config table of the output file header
**Total Fields:** 5
**Key Fields:** MANDT, SOURCEFROM, SOURCENAME, TARGETLOCATION

## Programs Using This Table
- `ziscs0099`
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `SOURCENAME` | CHAR | 100 | 🔑 | File name or Table name |
| 4 | `TARGETLOCATION` | CHAR | 100 | 🔑 | Folder location |
| 5 | `DELIMITED` | CHAR | 5 |  | Field Delimited Character |

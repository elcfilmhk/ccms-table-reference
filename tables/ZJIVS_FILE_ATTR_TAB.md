# ZJIVS_FILE_ATTR_TAB
**Description:** JiVS-Package: Attributes of all exported files in LOG file
**Total Fields:** 27
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_create_table_count`
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`
- `zjivs_export_setdata`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME` | CHAR | 49 |  | JiVS Dataelement for tablename |
| 2 | `TABNAME_DDIC` | CHAR | 49 |  | JiVS Dataelement for tablename |
| 3 | `TABNAME_FILE` | CHAR | 49 |  | JiVS Dataelement for tablename |
| 4 | `TABCLASS` | CHAR | 8 |  | Table Category |
| 5 | `COUNT_ROWS` | DEC | 15 |  | Number of exported data records |
| 6 | `COUNT_BYTES` | FLTP | 16 |  | Number of exported bytes |
| 7 | `COUNT_FILES_CSV1` | NUMC | 5 |  | Number of packages per file |
| 8 | `COUNT_FILES_CSV2` | NUMC | 5 |  | Number of packages per file |
| 9 | `COUNT_FILES_CSX` | NUMC | 5 |  | Number of packages per file |
| 10 | `START` | DEC | 21 |  | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| 11 | `END` | DEC | 21 |  | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| 12 | `TIME_DIFF` | DEC | 15 |  | Run time of export in milliseconds |
| 13 | `ENCODING` | STRG | 0 |  | Encoding String |
| 14 | `ENCODING_CSX` | STRG | 0 |  | &nbsp; |
| 15 | `ROW_DELIM` | CHAR | 10 |  | Operating system of application server |
| 16 | `FNAME_FULL_TEMPL` | CHAR | 128 |  | Local file for upload/download |
| 17 | `FNAME_SHORT_TEMPL` | CHAR | 128 |  | Local file for upload/download |
| 18 | `FILES_CSV1` | TTYP | 0 |  | JiVS-Package: Table type for ZJIVS_FILE_ATTR |
| 19 | `FILES_CSV2` | TTYP | 0 |  | JiVS-Package: Table type for ZJIVS_FILE_ATTR |
| 20 | `FILES_CSX` | TTYP | 0 |  | JiVS-Package: Table type for ZJIVS_FILE_ATTR |
| 21 | `COMPRESS` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 22 | `COMPRESS_ENCODING` | STRG | 0 |  | JIVS String |
| 23 | `COMPRESS_ENCODING_CSX` | STRG | 0 |  | JIVS String |
| 24 | `COMPRESS_LEVEL` | INT1 | 3 |  | JiVS compress level |
| 25 | `ZIP_PAC_SIZE` | NUMC | 8 |  | Package Size for ZIP |
| 26 | `OPEN_FILES` | DEC | 15 |  | Number of exported data records |
| 27 | `FNAME_WITH_SUFFIX` | CHAR | 1 |  | General Flag |

# ZJIVS_FILE_ATTR
**Description:** JiVS-Package: Attributes of exported files in .LOG file
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TYPE` | CHAR | 3 |  | Package ZZJIVS- Type of export file |
| 2 | `FILENAME_FULL` | CHAR | 128 |  | Local file for upload/download |
| 3 | `FILENAME` | STRG | 0 |  | File Name |
| 4 | `EXTENSION` | CHAR | 4 |  | File extension |
| 5 | `ENCODING` | STRG | 0 |  | Encoding String |
| 6 | `DELIMITER` | CHAR | 2 |  | Delimiter 2 chars |
| 7 | `LINE_DELIMITER` | CHAR | 10 |  | Operating system of application server |
| 8 | `COUNT_ROWS` | DEC | 15 |  | Number of exported data records |
| 9 | `COUNT_BYTES` | FLTP | 16 |  | Number of exported bytes |
| 10 | `START` | DEC | 21 |  | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| 11 | `END` | DEC | 21 |  | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| 12 | `FINISHED` | CHAR | 1 |  | Checkbox |
| 13 | `COMPRESS_COUNT` | INT4 | 10 |  | Natural number |
| 14 | `COMPRESS_DATA` | STRG | 0 |  | JIVS String |
| 15 | `COMPRESS_DATAX` | RSTR | 0 |  | JIVS XString |
| 16 | `DATASET_OPEN` | CHAR | 1 |  | Checkbox |
| 17 | `FILECOUNT` | NUMC | 5 |  | Number of packages per file |

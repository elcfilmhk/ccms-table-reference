# ZJIVS_SETTINGS
**Description:** Export options specific for one table
**Total Fields:** 40
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_create_exp_filters`
- `zjivs_create_table_count`
- `zjivs_export`
- `zjivs_export_arch_link`
- `zjivs_export_info`
- `zjivs_export_job`
- `zjivs_export_nast_to_pdf`
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`
- `zjivs_export_setdata`
- `zjivs_rollname`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME` | CHAR | 30 |  | Table Name |
| 2 | `.INCLUDE` | &nbsp; | 0 |  | Export options |
| 3 | `SERVERPATH` | CHAR | 50 |  | Server path |
| 4 | `FILEEXT` | CHAR | 4 |  | File extension |
| 5 | `DELIMITER` | CHAR | 2 |  | Delimiter 2 chars |
| 6 | `EXPORT_MODE` | CHAR | 6 |  | Export mode |
| 7 | `ENCODINGTYPE` | CHAR | 12 |  | Encoding type |
| 8 | `LINE_DELIMITER` | CHAR | 10 |  | Operating system of application server |
| 9 | `PACKSIZE` | NUMC | 8 |  | Package Size |
| 10 | `PACKFILE` | NUMC | 5 |  | Number of packages per file |
| 11 | `LSMWFILE` | CHAR | 1 |  | Create LSMW files |
| 12 | `SUPP_INIT_VAL` | CHAR | 1 |  | Suppress initial values |
| 13 | `INITIAL_FOR_PK` | CHAR | 1 |  | Initial values in primary key fields |
| 14 | `CHECK_FIELDS` | CHAR | 1 |  | Check for delimiter and command chars |
| 15 | `HEXA_EXPORT` | CHAR | 1 |  | Export in hexadecimal format |
| 16 | `FULL_LENGTH_CHAR` | CHAR | 1 |  | CHAR fields in full length |
| 17 | `CONV_DATE_TIME` | CHAR | 1 |  | Convert date and time to output format |
| 18 | `DATE_CHECK` | CHAR | 1 |  | Check date fields for illegal values |
| 19 | `ILLEGAL_DATE_VAL` | DATS | 8 |  | Value for illegal date values |
| 20 | `BASE64_EXPORT` | CHAR | 1 |  | Export with base64 coding |
| 21 | `BINARY_TO_HEX` | CHAR | 1 |  | Export binary field in hexadecimal format |
| 22 | `COMPRESS` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 23 | `COMPRESS_LEVEL` | INT1 | 3 |  | JiVS compress level |
| 24 | `ZIP_PAC_SIZE` | NUMC | 8 |  | Package Size for ZIP |
| 25 | `COMPRESS_LENGTH` | NUMC | 8 |  | JiVS max data length for compression |
| 26 | `SUPPRESS_UTF8` | CHAR | 1 |  | Jivs Flag for as UTF-16 |
| 27 | `KPRO_FILE` | CHAR | 1 |  | Jivs Flag for Export KPRO as File |
| 28 | `USE_FMT` | CHAR | 1 |  | Jivs Flag for Export with FMT |
| 29 | `USE_7ZIP` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 30 | `DOC_7Z_SIZE` | INT4 | 10 |  | Natural number |
| 31 | `DOC_MAX_FILES` | INT4 | 10 |  | Natural number |
| 32 | `HSDT_TABLE` | CHAR | 1 |  | General Flag |
| 33 | `ENDIAN_EXP` | CHAR | 1 |  | Endian |
| 34 | `DELIMITER_2` | CHAR | 2 |  | Delimiter 2 chars |
| 35 | `MAX_SIZE_MB_EXP` | INT4 | 10 |  | Maximum Size of an Archive File in Megabyte |
| 36 | `CASE_ID` | INT4 | 10 |  | JiVS DT OCC CASE ID |
| 37 | `OCC_SYSTEM_ID` | INT4 | 10 |  | JiVS DT OCC SYSTEM ID |
| 38 | `RUN_ID` | INT4 | 10 |  | &nbsp; |
| 39 | `CUSTOMER_ID` | INT4 | 10 |  | JiVS DT OCC CUSTOMER ID |
| 40 | `SERVERPATH2` | CHAR | 50 |  | Server path |

# ZJIVS_SETT
**Description:** Export options specific for one table
**Total Fields:** 42
**Key Fields:** MANDT, MIGOBJ, TABNAME

## Programs Using This Table
- `zcl_jivs_project_util`
- `zjivs_export`
- `zjivs_export_adk`
- `zjivs_export_adk_dispatcher`
- `zjivs_export_job`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Export options |
| 5 | `SERVERPATH` | CHAR | 50 |  | Server path |
| 6 | `FILEEXT` | CHAR | 4 |  | File extension |
| 7 | `DELIMITER` | CHAR | 2 |  | Delimiter 2 chars |
| 8 | `EXPORT_MODE` | CHAR | 6 |  | Export mode |
| 9 | `ENCODINGTYPE` | CHAR | 12 |  | Encoding type |
| 10 | `LINE_DELIMITER` | CHAR | 10 |  | Operating system of application server |
| 11 | `PACKSIZE` | NUMC | 8 |  | Package Size |
| 12 | `PACKFILE` | NUMC | 5 |  | Number of packages per file |
| 13 | `LSMWFILE` | CHAR | 1 |  | Create LSMW files |
| 14 | `SUPP_INIT_VAL` | CHAR | 1 |  | Suppress initial values |
| 15 | `INITIAL_FOR_PK` | CHAR | 1 |  | Initial values in primary key fields |
| 16 | `CHECK_FIELDS` | CHAR | 1 |  | Check for delimiter and command chars |
| 17 | `HEXA_EXPORT` | CHAR | 1 |  | Export in hexadecimal format |
| 18 | `FULL_LENGTH_CHAR` | CHAR | 1 |  | CHAR fields in full length |
| 19 | `CONV_DATE_TIME` | CHAR | 1 |  | Convert date and time to output format |
| 20 | `DATE_CHECK` | CHAR | 1 |  | Check date fields for illegal values |
| 21 | `ILLEGAL_DATE_VAL` | DATS | 8 |  | Value for illegal date values |
| 22 | `BASE64_EXPORT` | CHAR | 1 |  | Export with base64 coding |
| 23 | `BINARY_TO_HEX` | CHAR | 1 |  | Export binary field in hexadecimal format |
| 24 | `COMPRESS` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 25 | `COMPRESS_LEVEL` | INT1 | 3 |  | JiVS compress level |
| 26 | `ZIP_PAC_SIZE` | NUMC | 8 |  | Package Size for ZIP |
| 27 | `COMPRESS_LENGTH` | NUMC | 8 |  | JiVS max data length for compression |
| 28 | `SUPPRESS_UTF8` | CHAR | 1 |  | Jivs Flag for as UTF-16 |
| 29 | `KPRO_FILE` | CHAR | 1 |  | Jivs Flag for Export KPRO as File |
| 30 | `USE_FMT` | CHAR | 1 |  | Jivs Flag for Export with FMT |
| 31 | `USE_7ZIP` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 32 | `DOC_7Z_SIZE` | INT4 | 10 |  | Natural number |
| 33 | `DOC_MAX_FILES` | INT4 | 10 |  | Natural number |
| 34 | `HSDT_TABLE` | CHAR | 1 |  | General Flag |
| 35 | `ENDIAN_EXP` | CHAR | 1 |  | Endian |
| 36 | `DELIMITER_2` | CHAR | 2 |  | Delimiter 2 chars |
| 37 | `MAX_SIZE_MB_EXP` | INT4 | 10 |  | Maximum Size of an Archive File in Megabyte |
| 38 | `CASE_ID` | INT4 | 10 |  | JiVS DT OCC CASE ID |
| 39 | `OCC_SYSTEM_ID` | INT4 | 10 |  | JiVS DT OCC SYSTEM ID |
| 40 | `RUN_ID` | INT4 | 10 |  | &nbsp; |
| 41 | `CUSTOMER_ID` | INT4 | 10 |  | JiVS DT OCC CUSTOMER ID |
| 42 | `SERVERPATH2` | CHAR | 50 |  | Server path |

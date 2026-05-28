# ZJIVS_EXP_PROJECT_SETTINGS
**Description:** 
**Total Fields:** 63
**Key Fields:** _none_

## Programs Using This Table
- `zcl_jivs_project_util`
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `MIGOBJ` | CHAR | 15 |  | Object Name Definition |
| 3 | `EXP_RUNS` | INT4 | 10 |  | Natural number |
| 4 | `TABNAME` | CHAR | 30 |  | Table Name |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Export options |
| 6 | `SERVERPATH` | CHAR | 50 |  | Server path |
| 7 | `FILEEXT` | CHAR | 4 |  | File extension |
| 8 | `DELIMITER` | CHAR | 2 |  | Delimiter 2 chars |
| 9 | `EXPORT_MODE` | CHAR | 6 |  | Export mode |
| 10 | `ENCODINGTYPE` | CHAR | 12 |  | Encoding type |
| 11 | `LINE_DELIMITER` | CHAR | 10 |  | Operating system of application server |
| 12 | `PACKSIZE` | NUMC | 8 |  | Package Size |
| 13 | `PACKFILE` | NUMC | 5 |  | Number of packages per file |
| 14 | `LSMWFILE` | CHAR | 1 |  | Create LSMW files |
| 15 | `SUPP_INIT_VAL` | CHAR | 1 |  | Suppress initial values |
| 16 | `INITIAL_FOR_PK` | CHAR | 1 |  | Initial values in primary key fields |
| 17 | `CHECK_FIELDS` | CHAR | 1 |  | Check for delimiter and command chars |
| 18 | `HEXA_EXPORT` | CHAR | 1 |  | Export in hexadecimal format |
| 19 | `FULL_LENGTH_CHAR` | CHAR | 1 |  | CHAR fields in full length |
| 20 | `CONV_DATE_TIME` | CHAR | 1 |  | Convert date and time to output format |
| 21 | `DATE_CHECK` | CHAR | 1 |  | Check date fields for illegal values |
| 22 | `ILLEGAL_DATE_VAL` | DATS | 8 |  | Value for illegal date values |
| 23 | `BASE64_EXPORT` | CHAR | 1 |  | Export with base64 coding |
| 24 | `BINARY_TO_HEX` | CHAR | 1 |  | Export binary field in hexadecimal format |
| 25 | `COMPRESS` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 26 | `COMPRESS_LEVEL` | INT1 | 3 |  | JiVS compress level |
| 27 | `ZIP_PAC_SIZE` | NUMC | 8 |  | Package Size for ZIP |
| 28 | `COMPRESS_LENGTH` | NUMC | 8 |  | JiVS max data length for compression |
| 29 | `SUPPRESS_UTF8` | CHAR | 1 |  | Jivs Flag for as UTF-16 |
| 30 | `KPRO_FILE` | CHAR | 1 |  | Jivs Flag for Export KPRO as File |
| 31 | `USE_FMT` | CHAR | 1 |  | Jivs Flag for Export with FMT |
| 32 | `USE_7ZIP` | CHAR | 1 |  | Jivs Flag for export as ZIP file |
| 33 | `DOC_7Z_SIZE` | INT4 | 10 |  | Natural number |
| 34 | `DOC_MAX_FILES` | INT4 | 10 |  | Natural number |
| 35 | `HSDT_TABLE` | CHAR | 1 |  | General Flag |
| 36 | `ENDIAN_EXP` | CHAR | 1 |  | Endian |
| 37 | `DELIMITER_2` | CHAR | 2 |  | Delimiter 2 chars |
| 38 | `MAX_SIZE_MB_EXP` | INT4 | 10 |  | Maximum Size of an Archive File in Megabyte |
| 39 | `CASE_ID` | INT4 | 10 |  | JiVS DT OCC CASE ID |
| 40 | `OCC_SYSTEM_ID` | INT4 | 10 |  | JiVS DT OCC SYSTEM ID |
| 41 | `RUN_ID` | INT4 | 10 |  | &nbsp; |
| 42 | `CUSTOMER_ID` | INT4 | 10 |  | JiVS DT OCC CUSTOMER ID |
| 43 | `SERVERPATH2` | CHAR | 50 |  | Server path |
| 44 | `CSV_EXPORT` | CHAR | 1 |  | Checkbox |
| 45 | `EXPORT_JOBS` | INT4 | 10 |  | Natural number |
| 46 | `EXP_TAB_SEL` | CHAR | 1 |  | Checkbox |
| 47 | `EXP_ALL_TABS` | CHAR | 1 |  | Checkbox |
| 48 | `EXP_ALL_VIEWS` | CHAR | 1 |  | Checkbox |
| 49 | `EXP_CONTINUE` | CHAR | 1 |  | Checkbox |
| 50 | `OVERWRITE` | CHAR | 1 |  | Checkbox |
| 51 | `CONTINUE_COUNT` | CHAR | 1 |  | Checkbox |
| 52 | `STATUS_TXT` | CHAR | 60 |  | Short Text for Fixed Values |
| 53 | `TMD_VIEWS` | CHAR | 1 |  | Checkbox |
| 54 | `UPLOAD` | CHAR | 1 |  | Checkbox |
| 55 | `ZIPPER` | CHAR | 1 |  | Checkbox |
| 56 | `UPLOAD_VARIANT` | CHAR | 14 |  | Variant Name |
| 57 | `ZIPPER_VARIANT` | CHAR | 14 |  | Variant Name |
| 58 | `REPLICATE_VARIANT` | CHAR | 14 |  | Variant Name |
| 59 | `TOTALTABS` | INT4 | 10 |  | Natural number |
| 60 | `TOTALSAPTABS` | INT4 | 10 |  | Natural number |
| 61 | `LOAD_TAB_STAT` | CHAR | 1 |  | Checkbox |
| 62 | `LOAD_VIEWS` | CHAR | 1 |  | Checkbox |
| 63 | `TARGET_SERVER` | CHAR | 20 |  | Server Name |

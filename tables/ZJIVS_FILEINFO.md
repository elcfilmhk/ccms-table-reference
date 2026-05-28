# ZJIVS_FILEINFO
**Description:** Attributes of an operating system file
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_create_table_count`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TYPE` | CHAR | 10 |  | Type of a file in the operating system |
| 2 | `NAME` | CHAR | 255 |  | File Name |
| 3 | `LEN` | NUMC | 15 |  | Length of a file in bytes |
| 4 | `OWNER` | CHAR | 8 |  | Owner of a file (filename from operating system) |
| 5 | `MTIME` | NUMC | 10 |  | Last change date of a file in seconds since 1970 |
| 6 | `UMODE` | CHAR | 9 |  | File rights (ex. like in UNIX) |
| 7 | `SUBRC` | INT4 | 10 |  | Return Code |
| 8 | `ERRNO` | CHAR | 6 |  | SysLog: Operating system error number: "errno" |
| 9 | `ERRMSG` | CHAR | 40 |  | Error message for a file |
| 10 | `MOD_DATE` | DATS | 8 |  | Data on which a file was last changed |
| 11 | `MOD_TIME` | TIMS | 6 |  | Time when a file was last changed |

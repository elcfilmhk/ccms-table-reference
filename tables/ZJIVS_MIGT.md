# ZJIVS_MIGT
**Description:** Tables to be exported
**Total Fields:** 17
**Key Fields:** MANDT, MIGOBJ, TABNAME

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_export`
- `zjivs_export_arch_link`
- `zjivs_export_job`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `POSNR` | NUMC | 6 |  | Sort field |
| 5 | `SAPRL` | CHAR | 4 |  | SAP Release |
| 6 | `NROBJ` | CHAR | 10 |  | Name of number range object |
| 7 | `SUBOBJECT` | CHAR | 6 |  | Number range object subobject value |
| 8 | `NRRANGENR` | CHAR | 2 |  | Number range number |
| 9 | `TOYEAR` | NUMC | 4 |  | To fiscal year |
| 10 | `FROMNUMBER` | CHAR | 20 |  | From number |
| 11 | `TONUMBER` | CHAR | 20 |  | To number |
| 12 | `NRLEVEL` | NUMC | 20 |  | Number range status |
| 13 | `NRIND` | CHAR | 1 |  | Internal (' ') or external ('X') number range flag |
| 14 | `FILEPATH` | CHAR | 200 |  | Physical path name |
| 15 | `FILENAME` | CHAR | 60 |  | Physical file name |
| 16 | `DBSIZE` | NUMC | 20 |  | Size in bytes |
| 17 | `FILESIZE` | NUMC | 15 |  | Length of a file in bytes |

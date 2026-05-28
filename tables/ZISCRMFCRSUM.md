# ZISCRMFCRSUM
**Description:** First Contact Resolution (FCR) - Report Sum
**Total Fields:** 16
**Key Fields:** MANDT, ACTIVITY_FROM_DATE, ACTIVITY_TO_DATE, REPORT_TYPE, REPORT_SUB_TYPE

## Programs Using This Table
- `ziscrm0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACTIVITY_FROM_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `ACTIVITY_TO_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `REPORT_TYPE` | CHAR | 20 | 🔑 | Char 20 |
| 5 | `REPORT_SUB_TYPE` | CHAR | 30 | 🔑 | 30 Characters |
| 6 | `CIC_ALL` | INT4 | 10 |  | Natural number |
| 7 | `CSC_ALL` | INT4 | 10 |  | Natural number |
| 8 | `IVRS_ALL` | INT4 | 10 |  | Natural number |
| 9 | `WEB_ALL` | INT4 | 10 |  | Natural number |
| 10 | `MAIL_ALL` | INT4 | 10 |  | Natural number |
| 11 | `FAX_ALL` | INT4 | 10 |  | Natural number |
| 12 | `OTHERS_ALL` | INT4 | 10 |  | Natural number |
| 13 | `OVERALL_ALL` | INT4 | 10 |  | Natural number |
| 14 | `CREATE_DATE` | DATS | 8 |  | Date |
| 15 | `CREATE_TIME` | TIMS | 6 |  | Time |
| 16 | `CREATE_USER` | CHAR | 12 |  | User Name |

# ZISCRMFCRRPT
**Description:** First Contact Resolution (FCR) - Report
**Total Fields:** 20
**Key Fields:** MANDT, ACTIVITY_FROM_DATE, ACTIVITY_TO_DATE, REPORT_TYPE, ACTIVITY_GRP, ACTIVITY_SUB_CAT

## Programs Using This Table
- `ziscrm0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACTIVITY_FROM_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `ACTIVITY_TO_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `REPORT_TYPE` | CHAR | 20 | 🔑 | Char 20 |
| 5 | `ACTIVITY_GRP` | CHAR | 25 | 🔑 | Activity group |
| 6 | `ACTIVITY_SUB_CAT` | CHAR | 40 | 🔑 | Activity sub category |
| 7 | `CIC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 8 | `CIC_ALL` | INT4 | 10 |  | Natural number |
| 9 | `CSC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 10 | `CSC_ALL` | INT4 | 10 |  | Natural number |
| 11 | `IVRS` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 12 | `WEB` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 13 | `MAIL` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 14 | `FAX` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 15 | `OTHERS` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 16 | `OVERALL` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 17 | `TOTAL_TXN` | INT4 | 10 |  | Natural number |
| 18 | `CREATE_DATE` | DATS | 8 |  | Date |
| 19 | `CREATE_TIME` | TIMS | 6 |  | Time |
| 20 | `CREATE_USER` | CHAR | 12 |  | User Name |

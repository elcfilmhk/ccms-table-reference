# ZISSDEFTBANKDTL
**Description:** Bank details
**Total Fields:** 18
**Key Fields:** MANDT, SALES_ORDER_NO

## Programs Using This Table
- `zissd00065`
- `zissd00091`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 3 | `BANK_ACC_NO` | CHAR | 25 |  | Bank account no. |
| 4 | `CURRENCY` | CUKY | 5 |  | Transaction Currency |
| 5 | `AC_HOLDER` | CHAR | 60 |  | Account holder |
| 6 | `BANK_NAME` | CHAR | 60 |  | Bank name |
| 7 | `BANK_BRANCH` | CHAR | 60 |  | Bank branch |
| 8 | `BANK_ADDRESS` | CHAR | 100 |  | Bank address |
| 9 | `CITY` | CHAR | 40 |  | City |
| 10 | `REGION` | CHAR | 3 |  | Region |
| 11 | `COUNTRY` | CHAR | 40 |  | Country |
| 12 | `POSTAL_CODE` | CHAR | 16 |  | Postal Code |
| 13 | `CREATE_DATE` | DATS | 8 |  | Create date |
| 14 | `CREATE_TIME` | TIMS | 6 |  | Create time |
| 15 | `CREATE_BY` | CHAR | 12 |  | Create by |
| 16 | `LAST_UPD_DATE` | DATS | 8 |  | Last update date |
| 17 | `LAST_UPD_TIME` | TIMS | 6 |  | Last update time |
| 18 | `LAST_UPD_BY` | CHAR | 12 |  | Last updated by |

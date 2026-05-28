# ZISCRMFCRACTVREC
**Description:** First Contact Resolution (FCR) - Activity Record
**Total Fields:** 9
**Key Fields:** MANDT, FCR_NO

## Programs Using This Table
- `ziscrm0001`
- `ziscrm0002`
- `ziscrm0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FCR_NO` | NUMC | 10 | 🔑 | First Contact Resolution (FCR) number |
| 3 | `ACTIVITY_NO` | CHAR | 10 |  | Activity number |
| 4 | `CREATED_AT` | DEC | 15 |  | Created At (Output in User Time Zone) |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `CREATED_BY` | CHAR | 12 |  | User that Created the Transaction |
| 7 | `CHANNEL` | CHAR | 20 |  | Channel (Activity category) |
| 8 | `ACTIVITY_SUB_CAT` | CHAR | 40 |  | Activity sub category |
| 9 | `PARTNER` | CHAR | 10 |  | Business Partner Number |

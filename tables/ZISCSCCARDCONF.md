# ZISCSCCARDCONF
**Description:** Credit card enrollment program Configuration
**Total Fields:** 12
**Key Fields:** MANDT, ZAGENT_ID

## Programs Using This Table
- `zisfi0333`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZAGENT_ID` | CHAR | 10 | 🔑 | Agent ID |
| 3 | `ZCHANNEL_NAME` | CHAR | 25 |  | Channel name |
| 4 | `ZVALID_FROM` | DATS | 8 |  | Valid From Date |
| 5 | `ZVALID_TO` | DATS | 8 |  | Valid To Date |
| 6 | `ZCARD_LEN` | CHAR | 10 |  | Card length |
| 7 | `ZCARD_NUM_VAL` | CHAR | 10 |  | Card Number Validation |
| 8 | `ZAPP_DATE` | CHAR | 25 |  | Application Date |
| 9 | `ZIFUNC` | CHAR | 4 |  | Function name inbound |
| 10 | `ZOFUNC` | CHAR | 4 |  | Function name outbound |
| 11 | `ZEZAWE` | CHAR | 3 |  | Payment Method |
| 12 | `ZISSUER` | CHAR | 40 |  | Payment cards: Issuing bank |

# ZISCRMMYWSMSPLAN
**Description:** CRM My Workspace Plan Master
**Total Fields:** 7
**Key Fields:** MANDT, PLANID

## Programs Using This Table
- `ziscrm0010`
- `ziscrm0031`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PLANID` | CHAR | 12 | 🔑 | Plan ID |
| 3 | `DESCR` | CHAR | 30 |  | Description |
| 4 | `TYPE` | CHAR | 1 |  | Plan type |
| 5 | `PAID` | CHAR | 1 |  | Flag for paid service |
| 6 | `PLANID_P` | CHAR | 12 |  | Parent Plan ID |
| 7 | `AMOUNT` | CURR | 13 |  | Amount |

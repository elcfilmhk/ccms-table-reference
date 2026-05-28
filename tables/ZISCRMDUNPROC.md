# ZISCRMDUNPROC
**Description:** Fix the dunning procedure issue
**Total Fields:** 6
**Key Fields:** MANDT, VERTRAG

## Programs Using This Table
- `ziscrm0046`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `MOVEIN_DATE` | DATS | 8 |  | Move-In Date |
| 4 | `CREATE_DATE` | DATS | 8 |  | Date |
| 5 | `CREATE_TIME` | TIMS | 6 |  | Time |
| 6 | `USER_ID` | CHAR | 12 |  | User Name |

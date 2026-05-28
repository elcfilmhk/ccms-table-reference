# ZISMDCONVINST_R1
**Description:** Storing the output interface file record
**Total Fields:** 10
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zismd0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERVPT_TEXT` | CHAR | 100 |  | Service point description |
| 4 | `VUSER` | CHAR | 16 |  | Validate User |
| 5 | `VSTELLE` | CHAR | 10 |  | Premise |
| 6 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `TASKOPERATION` | CHAR | 10 |  | Task Operation |

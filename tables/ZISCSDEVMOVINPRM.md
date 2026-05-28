# ZISCSDEVMOVINPRM
**Description:** Developer move in deposit coverage
**Total Fields:** 10
**Key Fields:** MANDT, SECURITY, SEQUENCE_NO

## Programs Using This Table
- `ziscs0207`
- `ziscs0213`
- `ziscs0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SECURITY` | CHAR | 12 | 🔑 | Security Deposit |
| 3 | `SEQUENCE_NO` | INT4 | 10 | 🔑 | Sequence no. |
| 4 | `STREET_3` | CHAR | 40 |  | Street 3 |
| 5 | `PREMISE_ID` | CHAR | 10 |  | Premise |
| 6 | `METER_NO` | CHAR | 18 |  | Equipment Number |
| 7 | `CONTRACT` | CHAR | 10 |  | Contract |
| 8 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 9 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 10 | `CONT_ACC` | CHAR | 12 |  | Contract Account Number |

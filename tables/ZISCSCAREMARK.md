# ZISCSCAREMARK
**Description:** Contract Account Remark
**Total Fields:** 15
**Key Fields:** MANDT, CA, SEQNUM

## Programs Using This Table
- `zaccount`
- `zisbi0200`
- `ziscrm0030`
- `ziscs_migration_custcontact_m4`
- `zisfi0155`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SEQNUM` | NUMC | 6 | 🔑 | Item number |
| 4 | `VALID_FROM` | DATS | 8 |  | Effective date |
| 5 | `VALID_TO` | DATS | 8 |  | Expiry date |
| 6 | `SHORT_TEXT` | CHAR | 70 |  | Short text |
| 7 | `LONG_TEXT_1` | CHAR | 70 |  | Long text line 1 |
| 8 | `LONG_TEXT_2` | CHAR | 70 |  | Long text line 2 |
| 9 | `LONG_TEXT_3` | CHAR | 70 |  | Long text line 3 |
| 10 | `CREATE_DATE` | DATS | 8 |  | Created on |
| 11 | `CREATE_TIME` | TIMS | 6 |  | Time of creation |
| 12 | `CREATE_BY` | CHAR | 12 |  | Created by |
| 13 | `LAST_CHG_DATE` | DATS | 8 |  | Changed on |
| 14 | `LAST_CHG_TIME` | TIMS | 6 |  | Time of change |
| 15 | `LAST_CHG_BY` | CHAR | 12 |  | Last changed by |

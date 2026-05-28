# ZISCS_PC_TOK
**Description:** Power Connect Token table
**Total Fields:** 14
**Key Fields:** MANDT, TOKEN

## Programs Using This Table
- `ziscs0801`
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscs1031`
- `ziscs1033`
- `ziscspc_resolve_token=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TOKEN` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 3 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 4 | `CA` | CHAR | 12 |  | Contract Account Number |
| 5 | `BPNAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 6 | `EMAILID` | CHAR | 241 |  | E-Mail Address |
| 7 | `PHONE` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 8 | `VALUE5` | CHAR | 100 |  | Value |
| 9 | `VALID_TO_DT` | DATS | 8 |  | Valid To Date |
| 10 | `VALID_TO_TIME` | TIMS | 6 |  | Valid To Time |
| 11 | `STATUS` | CHAR | 1 |  | Status |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERZET` | TIMS | 6 |  | Entry time |
| 14 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

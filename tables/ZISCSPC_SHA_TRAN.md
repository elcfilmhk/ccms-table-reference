# ZISCSPC_SHA_TRAN
**Description:** Shared Function Transaction Table
**Total Fields:** 9
**Key Fields:** MANDT, PROG_ID, CANUMBER, EMAILID

## Programs Using This Table
- `zcl_zgws_mpc`
- `ziscspc_comm_frmwrk_trigger===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `CANUMBER` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EMAILID` | CHAR | 100 | 🔑 | Customer Email ID |
| 5 | `REF_CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 6 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 7 | `JOINING_STATUS` | CHAR | 1 |  | Joining Status |
| 8 | `SHARING_DATE` | DATS | 8 |  | Sharing Date |
| 9 | `JOINING_DATE` | DATS | 8 |  | Joining Date |

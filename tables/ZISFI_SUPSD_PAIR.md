# ZISFI_SUPSD_PAIR
**Description:** Government Supplementary Subsidy Pairing for FI
**Total Fields:** 13
**Key Fields:** MANDT, REF_NO

## Programs Using This Table
- `zisfi0165`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REF_NO` | NUMC | 8 | 🔑 | Reference no. |
| 3 | `CA_OLD` | CHAR | 12 |  | Transfer From Contract Account (Old) |
| 4 | `CA_NEW` | CHAR | 12 |  | Transfer To Contract Account (New) |
| 5 | `SECURITY` | CHAR | 12 |  | Security Deposit |
| 6 | `REQUEST` | CURR | 11 |  | Requested Amount for Security Deposit |
| 7 | `ZDSDATE` | DATS | 8 |  | Security Deposit Creation Date |
| 8 | `ZDSTIME` | TIMS | 6 |  | Security Deposit Creation Time |
| 9 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 10 | `ZCRAMT` | CURR | 13 |  | Credit Amount in Local Currency |
| 11 | `ZDRAMT` | CURR | 13 |  | Debit Amount in Local Currency |
| 12 | `ZTRDATE` | DATS | 8 |  | Transfer document Creation Date |
| 13 | `ZTRTIME` | TIMS | 6 |  | Transfer document Creation Time |

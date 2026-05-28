# ZISDMDEMSACCT
**Description:** CA to be processed with DEMS
**Total Fields:** 3
**Key Fields:** MANDT, VKONTO

## Programs Using This Table
- `zisdm0231`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REMARK` | CHAR | 80 |  | DEMS remark for the account |

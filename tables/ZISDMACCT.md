# ZISDMACCT
**Description:** Account Table
**Total Fields:** 10
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0021`
- `zisdm0039`
- `zisdm0058`
- `zisdm0075`
- `zisdm0090`
- `zisdm0091`
- `zisdm0098`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `KTOKL` | CHAR | 4 |  | Account class |
| 4 | `AD_TITLE` | CHAR | 4 |  | Form-of-Address Key |
| 5 | `VKBEZ` | CHAR | 35 |  | Contract Account Name |
| 6 | `BP_NAME` | CHAR | 81 |  | Name of Business Partner |
| 7 | `ADDRESS1` | CHAR | 40 |  | Street 1 |
| 8 | `ADDRESS2` | CHAR | 40 |  | Street 2 |
| 9 | `ADDRESS3` | CHAR | 40 |  | Street 3 |
| 10 | `ADDRESS4` | CHAR | 40 |  | Street 4 |

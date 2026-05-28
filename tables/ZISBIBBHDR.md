# ZISBIBBHDR
**Description:** Budget Billing header
**Total Fields:** 26
**Key Fields:** MANDT, OPBEL, VKONT

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `PREISBTR` | DEC | 17 |  | Price amount |
| 5 | `N_EFFDATE` | DATS | 8 |  | New Rate Effective Date |
| 6 | `N_EFFDATE1` | DATS | 8 |  | New Rate Effective Date |
| 7 | `BF_AMT` | CURR | 13 |  | Net amount of billing line item |
| 8 | `CURR_AMT` | CURR | 13 |  | Net amount of billing line item |
| 9 | `DUE_DATE` | DATS | 8 |  | Due Date |
| 10 | `INSTALL_AMT` | CURR | 13 |  | Net amount of billing line item |
| 11 | `TOTAL` | CURR | 13 |  | Net amount of billing line item |
| 12 | `EMESG1` | CHAR | 100 |  | English Message |
| 13 | `EMESG2` | CHAR | 100 |  | English Message |
| 14 | `EMESG3` | CHAR | 100 |  | English Message |
| 15 | `EMESG4` | CHAR | 100 |  | English Message |
| 16 | `EMESG5` | CHAR | 100 |  | English Message |
| 17 | `EMESG6` | CHAR | 100 |  | English Message |
| 18 | `EMESG7` | CHAR | 100 |  | English Message |
| 19 | `CMESG1` | CHAR | 100 |  | Chinese Message |
| 20 | `CMESG2` | CHAR | 100 |  | Chinese Message |
| 21 | `CMESG3` | CHAR | 100 |  | Chinese Message |
| 22 | `CMESG4` | CHAR | 100 |  | Chinese Message |
| 23 | `CMESG5` | CHAR | 100 |  | Chinese Message |
| 24 | `CMESG6` | CHAR | 100 |  | Chinese Message |
| 25 | `CMESG7` | CHAR | 100 |  | Chinese Message |
| 26 | `PAYMETHOD` | CHAR | 3 |  | Payment Method |

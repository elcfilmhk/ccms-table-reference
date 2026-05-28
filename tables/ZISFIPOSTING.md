# ZISFIPOSTING
**Description:** Rebate posting
**Total Fields:** 13
**Key Fields:** MANDT, ZZCREATIONDATE, ZZREBATE_REF, VKONT

## Programs Using This Table
- `zisbi0108`
- `zisbi0110`
- `zisbi0110_2`
- `ziscs0170`
- `ziscs0172`
- `ziscs0178`
- `ziscs0187`
- `ziscs0210`
- `zisfi0138`
- `zisfi0141_bkgrd`
- `zisfi0247`
- `zissd00112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZCREATIONDATE` | DATS | 8 | 🔑 | Creation date |
| 3 | `ZZREBATE_REF` | CHAR | 16 | 🔑 | Rebate reference |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `ZZREBATE_AMT` | CURR | 13 |  | Rebate amount |
| 6 | `VERTRAG` | CHAR | 10 |  | Contract |
| 7 | `ZZPOSDATE` | DATS | 8 |  | Posting Date |
| 8 | `ZZREBATE_STATUS` | CHAR | 1 |  | Rebate status |
| 9 | `ZZUPDATEDATE` | DATS | 8 |  | Last update date |
| 10 | `ZZTEXT` | CHAR | 100 |  | Text |
| 11 | `APPNO` | CHAR | 10 |  | Application no. |
| 12 | `SCHNO` | CHAR | 10 |  | Bonus Scheme Number |
| 13 | `INSTM` | CHAR | 4 |  | Bonus installment |

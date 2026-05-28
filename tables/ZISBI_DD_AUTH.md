# ZISBI_DD_AUTH
**Description:** Structure to print DD Authorization Form
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `ztest_sapmzcs380`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `APYBNO` | CHAR | 15 |  | Bank Keys |
| 3 | `APYBRCHNO` | CHAR | 18 |  | Bank account number |
| 4 | `APYBAN` | CHAR | 18 |  | Bank account number |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `APYHLDNAME1` | CHAR | 60 |  | Account Holder Name |
| 7 | `APYHLDNAME2` | CHAR | 60 |  | Account Holder Name |
| 8 | `RETURN_CODE` | CHAR | 1 |  | Return Code (0=Success, 8 = Fail) |
| 9 | `RETURN_MESSAGE` | CHAR | 220 |  | Message Text |

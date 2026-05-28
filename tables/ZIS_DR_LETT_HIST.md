# ZIS_DR_LETT_HIST
**Description:** Table for AMI generic Welcome pack and Event Result
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, TYPE_OF_LETTER, YEAR_OF_LETTER

## Programs Using This Table
- `zisdm0374`
- `zisdm0385`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE_OF_LETTER` | CHAR | 2 | 🔑 | Letter Type |
| 4 | `YEAR_OF_LETTER` | CHAR | 4 | 🔑 | Year |
| 5 | `EMAIL_OR_LETTER` | CHAR | 2 |  | Email/Direct letters |
| 6 | `LETTER_SENT_DATE` | DATS | 8 |  | Date on which letter is sent |
| 7 | `USER_ID` | CHAR | 10 |  | User ID |
| 8 | `TIMESTAMP` | CHAR | 14 |  | Timestamp |
| 9 | `SPOOLID` | NUMC | 10 |  | Extended spool ID |
| 10 | `RCVTMESTMP` | CHAR | 14 |  | Streamserve Timestamp |
| 11 | `STATUS` | CHAR | 10 |  | Status |

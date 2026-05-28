# ZISDMADRDRCUPDCC
**Description:** DR Customer Privileged Data Change Control table
**Total Fields:** 40
**Key Fields:** MANDT, DRCUSTNO

## Programs Using This Table
- `zisdm0309`
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `DRCUSTNAME` | CHAR | 80 |  | DR Customer name |
| 4 | `PAYEENAME` | CHAR | 80 |  | Payee Name |
| 5 | `ADDRESS` | CHAR | 100 |  | Customer Address |
| 6 | `BASELINE` | CHAR | 10 |  | Baseline Method |
| 7 | `REFCA` | CHAR | 12 |  | Contract Account Number |
| 8 | `MAXCUT` | DEC | 8 |  | ADR Max/Target Cut value |
| 9 | `PROG_NAME` | CHAR | 3 |  | Program Name |
| 10 | `CUSTCODE` | CHAR | 11 |  | Customer Code |
| 11 | `CUST_ALIAS` | CHAR | 100 |  | Customer Alias |
| 12 | `CUST_TRADE` | CHAR | 30 |  | Customer Trade |
| 13 | `AGREEMENT_EFF_DT` | DATS | 8 |  | Agreement Effect Date |
| 14 | `AGREEMENT_EXP_DT` | DATS | 8 |  | Agreement Expiry Date |
| 15 | `METER_TYPE` | CHAR | 20 |  | Meter Type |
| 16 | `DMRED11T12` | DEC | 8 |  | Target Demand Reduction Per HR |
| 17 | `DMRED12T13` | DEC | 8 |  | Target Demand Reduction Per HR |
| 18 | `DMRED13T14` | DEC | 8 |  | Target Demand Reduction Per HR |
| 19 | `DMRED14T15` | DEC | 8 |  | Target Demand Reduction Per HR |
| 20 | `DMRED15T16` | DEC | 8 |  | Target Demand Reduction Per HR |
| 21 | `DMRED16T17` | DEC | 8 |  | Target Demand Reduction Per HR |
| 22 | `DMRED17T18` | DEC | 8 |  | Target Demand Reduction Per HR |
| 23 | `DMRED18T19` | DEC | 8 |  | Target Demand Reduction Per HR |
| 24 | `DMRED19T20` | DEC | 8 |  | Target Demand Reduction Per HR |
| 25 | `DMRED20T21` | DEC | 8 |  | Target Demand Reduction Per HR |
| 26 | `DMRED21T22` | DEC | 8 |  | Target Demand Reduction Per HR |
| 27 | `BRANCH` | CHAR | 5 |  | Branch ID |
| 28 | `BACKUP_PERSON1` | CHAR | 60 |  | Name of Contact Person |
| 29 | `BACKUP_PHONE1` | CHAR | 50 |  | Contact Information |
| 30 | `BACKUP_PERSON2` | CHAR | 60 |  | Name of Contact Person |
| 31 | `BACKUP_PHONE2` | CHAR | 50 |  | Contact Information |
| 32 | `PAYMENT_OPTION` | CHAR | 2 |  | DR Customer payment option |
| 33 | `PREF_CHANNEL` | CHAR | 1 |  | Preferred Channel for Communication |
| 34 | `CHEQUE_ADDR1` | CHAR | 35 |  | Cheque Address |
| 35 | `CHEQUE_ADDR2` | CHAR | 35 |  | Cheque Address |
| 36 | `CHEQUE_COUNTRY` | CHAR | 3 |  | Country Key |
| 37 | `ACTION` | CHAR | 1 |  | DR Customer information update type method |
| 38 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 39 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 40 | `AENAM` | CHAR | 12 |  | Name of person who changed object |

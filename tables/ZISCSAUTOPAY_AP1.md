# ZISCSAUTOPAY_AP1
**Description:** Online Autopay Application
**Total Fields:** 31
**Key Fields:** MANDT, BUSINESSPARTNER, CONTRACTACCOUNT, ERDAT, ERZET

## Programs Using This Table
- `ztest_sapmzcs380`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUSINESSPARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `CONTRACTACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `ENG_NAME` | CHAR | 140 |  | English Name for DDA registration |
| 11 | `CONTACT` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 12 | `EMAIL` | CHAR | 241 |  | E-Mail Address |
| 13 | `APYBNO` | CHAR | 15 |  | Bank Keys |
| 14 | `APYBRCHNO` | CHAR | 18 |  | Bank account number |
| 15 | `APYBAN` | CHAR | 18 |  | Bank account number |
| 16 | `APYHLDNAME1` | CHAR | 140 |  | Account Holder Name 1 & 2 for DDA registration |
| 17 | `APYHLDIDT1` | CHAR | 6 |  | Identification Type |
| 18 | `APYHLDID1` | CHAR | 60 |  | Identification Number |
| 19 | `APYHLDNAME2` | CHAR | 140 |  | Account Holder Name 1 & 2 for DDA registration |
| 20 | `APYHLDIDT2` | CHAR | 6 |  | Identification Type |
| 21 | `APYHLDID2` | CHAR | 60 |  | Identification Number |
| 22 | `STATUS` | CHAR | 1 |  | Autopay Application Status |
| 23 | `COKEY` | CHAR | 36 |  | Correspondence key |
| 24 | `CHANNEL` | CHAR | 40 |  | Channel |
| 25 | `CELLING` | CHAR | 1 |  | Incoming Payment Method |
| 26 | `REQEFFDAT` | DATS | 8 |  | Date |
| 27 | `EFFDAT` | DATS | 8 |  | Date |
| 28 | `ADDRESS` | CHAR | 60 |  | BP: Address Description |
| 29 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 30 | `SCHBILLDATE` | DATS | 8 |  | Date |
| 31 | `DEBTOR_REF` | CHAR | 35 |  | Debtor Reference(CA with special Chars "Space - ") |

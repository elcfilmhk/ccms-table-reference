# ZISCS_BNFCRY_PAY
**Description:** Payment Data of Eligible Beneficiaries
**Total Fields:** 26
**Key Fields:** MANDT, PROG_ID, VKONT, PAY_ID, APPLN_REF

## Programs Using This Table
- `ziscs0800`
- `zisfi0305`
- `zisfi0341`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `PAY_ID` | CHAR | 8 | 🔑 | Payment Run ID |
| 5 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 6 | `PAY_DATE` | DATS | 8 |  | Payment Date |
| 7 | `PAY_AMOUNT` | CURR | 9 |  | Payment Amount |
| 8 | `CURRENCY` | CUKY | 5 |  | SD Document Currency |
| 9 | `CHQ_DATE` | DATS | 8 |  | Check Issue Date |
| 10 | `SUBMITTED_BY` | CHAR | 12 |  | Submitted By |
| 11 | `SUBMITTED_ON` | DATS | 8 |  | Submitted On |
| 12 | `APPROVED_BY` | CHAR | 12 |  | Approved By |
| 13 | `APPROVED_ON` | DATS | 8 |  | Approved On |
| 14 | `REJECTED_BY` | CHAR | 12 |  | Rejected By |
| 15 | `REJECTED_ON` | DATS | 8 |  | Rejected On |
| 16 | `APPLN_DATE` | DATS | 8 |  | Application Date |
| 17 | `DOC_NO` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 18 | `PAY_STATUS` | CHAR | 2 |  | Payment Status ID |
| 19 | `REMARK` | CHAR | 50 |  | Remark |
| 20 | `RANK` | NUMC | 8 |  | RANK |
| 21 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 22 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 23 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 24 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 25 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 26 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |

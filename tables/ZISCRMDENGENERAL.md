# ZISCRMDENGENERAL
**Description:** Data Enrichment - CA's General info
**Total Fields:** 36
**Key Fields:** MANDT, BP, CA

## Programs Using This Table
- `ziscrm0006`
- `ziscrm0007`
- `ziscrm0008`
- `ziscs0214`
- `zisfi0346`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BP` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CA_NAME` | CHAR | 100 |  | Contract Account Name |
| 5 | `CA_TEL1` | CHAR | 30 |  | CA Telephone 1 |
| 6 | `CA_TEL2` | CHAR | 30 |  | CA Telephone 2 |
| 7 | `CA_FAX` | CHAR | 30 |  | CA Fax Number |
| 8 | `CA_BR` | CHAR | 60 |  | BR Number |
| 9 | `CP1` | CHAR | 40 |  | Contact Person 1 Name |
| 10 | `CP1_TITLE` | CHAR | 30 |  | CP1 Title |
| 11 | `CP1_TEL1` | CHAR | 30 |  | CP1 Telephone 1 |
| 12 | `CP1_TEL2` | CHAR | 30 |  | CP1 Telephone 2 |
| 13 | `CP1_EMAIL` | CHAR | 241 |  | CP1 E-Mail Address |
| 14 | `PREM_OWNERP` | CHAR | 4 |  | Premise Ownership |
| 15 | `HSIC` | CHAR | 7 |  | HSIC |
| 16 | `PREM_FUNCTION` | CHAR | 4 |  | Premise Function |
| 17 | `FUTURE_PLAN1` | CHAR | 4 |  | Future Plan 1 |
| 18 | `FUTURE_PLAN2` | CHAR | 4 |  | Future Plan 2 |
| 19 | `BUS_UNIT` | CHAR | 4 |  | Business Unit |
| 20 | `BUS_UNIT_NO` | NUMC | 9 |  | No. of Unit |
| 21 | `CA_ASS_MEMBER` | CHAR | 70 |  | CAs Trade Asso. Membership |
| 22 | `CP1_ASS_MEMBER` | CHAR | 70 |  | CP1s Trade Asso. Membership |
| 23 | `LEASE_TERM` | NUMC | 4 |  | Lease Term |
| 24 | `EXPENDITURE1` | DEC | 15 |  | Data Enrichment - Expenditure 1 (Gas) |
| 25 | `EXPENDITURE2` | DEC | 15 |  | Data Enrichment - Expenditure 2 (Petrol) |
| 26 | `EXPENDITURE3` | DEC | 15 |  | Data Enrichment - Expenditure 3 (IDO) |
| 27 | `EXPENDITURE4` | DEC | 15 |  | Data Enrichment - Expenditure 4 (Others) |
| 28 | `EXPENDITURE5` | DEC | 15 |  | Data Enrichment - Expenditure 5 |
| 29 | `EXPENDITURE6` | DEC | 15 |  | Data Enrichment - Expenditure 6 |
| 30 | `EXPENDITURE7` | DEC | 15 |  | Data Enrichment - Expenditure 7 |
| 31 | `LAST_CHANGE_BY` | CHAR | 12 |  | User name of the person responsible in change document |
| 32 | `LAST_CHANGE_DATE` | DATS | 8 |  | Creation date of the change document |
| 33 | `LAST_CHANGE_TIME` | TIMS | 6 |  | Time changed |
| 34 | `CREATE_BY` | CHAR | 12 |  | User name of the person responsible in change document |
| 35 | `CREATE_DATE` | DATS | 8 |  | Creation date of the change document |
| 36 | `CREATE_TIME` | TIMS | 6 |  | Time changed |

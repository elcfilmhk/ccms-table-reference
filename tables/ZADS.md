# ZADS
**Description:** Analytical Data Storage: ZADS
**Total Fields:** 118
**Key Fields:** CLIENT, F_0BP_GUID, F_0CRM_BUAG

## Programs Using This Table
- `zads_bp_count`
- `ziscrm0314`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | &nbsp; |
| 2 | `F_0BP_GUID` | RAW | 16 | 🔑 | Business Partner GUID |
| 3 | `F_0CRM_BUAG` | CHAR | 32 | 🔑 | Business Agreement GUID |
| 4 | `F_0BPARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `F_0CRMBUAG_ID` | CHAR | 12 |  | Number of Business Agreement |
| 6 | `F_0UCRATE_CAT` | CHAR | 10 |  | Rate Category |
| 7 | `F_ZCMLANGU` | CHAR | 1 |  | Bill Language |
| 8 | `F_ZCMEMLPVD` | CHAR | 60 |  | Email Address Service Provider |
| 9 | `F_ZCMTRACAT` | CHAR | 2 |  | Trade Category |
| 10 | `F_ZCMTRACLA` | CHAR | 10 |  | Trade |
| 11 | `F_ZCMTRDCLS` | CHAR | 2 |  | Trade Class |
| 12 | `F_ZCMPERFUN` | CHAR | 3 |  | Premise Function |
| 13 | `F_0UCACC_CLAS` | CHAR | 4 |  | Account Class |
| 14 | `F_0FCACTDETID` | CHAR | 2 |  | Account Determination ID for Contract Account |
| 15 | `F_ZCMSENDCO` | CHAR | 4 |  | Dispatch Control |
| 16 | `F_0UCMOVEIN_D` | DATS | 8 |  | Move-In Date |
| 17 | `F_0UCMOVEOUTD` | DATS | 8 |  | Move-Out Date |
| 18 | `F_0UCBILL_CLA` | CHAR | 4 |  | Billing Class |
| 19 | `F_0UCPREMISTY` | CHAR | 8 |  | Premise Type |
| 20 | `F_0REGIO_GRP` | CHAR | 8 |  | Regional Structure Grouping |
| 21 | `F_ZCMDEL_M` | CHAR | 1 |  | Bill Delivery Method |
| 22 | `F_ZCMFLAECH` | CHAR | 12 |  | Floor Area in Square Meters |
| 23 | `F_ZCMACCACT` | CHAR | 1 |  | Account Active Indicator |
| 24 | `F_ZCMSEGLBL` | CHAR | 3 |  | Segment Label - Customer Segment |
| 25 | `F_ZCMHSELBL` | CHAR | 3 |  | Segment Label - Household |
| 26 | `F_ZCMACCTMG` | CHAR | 10 |  | Account Manager (BP Number) |
| 27 | `F_0FC_EZAWE` | CHAR | 1 |  | Incoming Payment Method |
| 28 | `F_0UCPYTERMS` | CHAR | 4 |  | Payment Terms |
| 29 | `F_ZCMMKTPMF` | CHAR | 1 |  | Marketing Permission |
| 30 | `F_ZCMB1TTL` | DEC | 17 |  | BP Set 1 Total Count |
| 31 | `F_ZCMB1SBTA` | DEC | 17 |  | BP Set 1 Sub Total A |
| 32 | `F_ZCMB1SBTB` | DEC | 17 |  | BP Set 1 Sub Total B |
| 33 | `F_ZCMB1EML` | DEC | 17 |  | BP Set 1 Email |
| 34 | `F_ZCMB1SMS` | DEC | 17 |  | BP Set 1 SMS |
| 35 | `F_ZCMB1WEB` | DEC | 17 |  | BP Set 1 Web |
| 36 | `F_ZCMB1SOMD` | DEC | 17 |  | BP Set 1 Social Media |
| 37 | `F_ZCMB1MOB` | DEC | 17 |  | BP Set 1 Mobile |
| 38 | `F_ZCMB1TEL` | DEC | 17 |  | BP Set 1 Telephone |
| 39 | `F_ZCMB1MAIL` | DEC | 17 |  | BP Set 1 Mail |
| 40 | `F_ZCMC1TTL` | DEC | 17 |  | CA Set 1 Total Count |
| 41 | `F_ZCMC1SBTA` | DEC | 17 |  | CA Set 1 Sub Total A |
| 42 | `F_ZCMC1SBTB` | DEC | 17 |  | CA Set 1 Sub Total B |
| 43 | `F_ZCMC1EML` | DEC | 17 |  | CA Set 1 Email |
| 44 | `F_ZCMC1SMS` | DEC | 17 |  | CA Set 1 SMS |
| 45 | `F_ZCMC1WEB` | DEC | 17 |  | CA Set 1 Web |
| 46 | `F_ZCMC1SOMD` | DEC | 17 |  | CA Set 1 Social Media |
| 47 | `F_ZCMC1MOB` | DEC | 17 |  | CA Set 1 Mobile |
| 48 | `F_ZCMC1TEL` | DEC | 17 |  | CA Set 1 Telephone |
| 49 | `F_ZCMC1MAIL` | DEC | 17 |  | CA Set 1 Mail |
| 50 | `F_ZCMB2TTL` | DEC | 17 |  | BP Set 2 Total Count |
| 51 | `F_ZCMB2SBTA` | DEC | 17 |  | BP Set 2 Sub Total A |
| 52 | `F_ZCMB2SBTB` | DEC | 17 |  | BP Set 2 Sub Total B |
| 53 | `F_ZCMB2EML` | DEC | 17 |  | BP Set 2 Email |
| 54 | `F_ZCMB2SMS` | DEC | 17 |  | BP Set 2 SMS |
| 55 | `F_ZCMB2WEB` | DEC | 17 |  | BP Set 2 Web |
| 56 | `F_ZCMB2SOMD` | DEC | 17 |  | BP Set 2 Social Media |
| 57 | `F_ZCMB2MOB` | DEC | 17 |  | BP Set 2 Mobile |
| 58 | `F_ZCMB2TEL` | DEC | 17 |  | BP Set 2 Telephone |
| 59 | `F_ZCMB2MAIL` | DEC | 17 |  | BP Set 2 Mail |
| 60 | `F_ZCMC2TTL` | DEC | 17 |  | CA Set 2 Total Count |
| 61 | `F_ZCMC2SBTA` | DEC | 17 |  | CA Set 2 Sub Total A |
| 62 | `F_ZCMC2SBTB` | DEC | 17 |  | CA Set 2 Sub Total B |
| 63 | `F_ZCMC2EML` | DEC | 17 |  | CA Set 2 Email |
| 64 | `F_ZCMC2SMS` | DEC | 17 |  | CA Set 2 SMS |
| 65 | `F_ZCMC2WEB` | DEC | 17 |  | CA Set 2 Web |
| 66 | `F_ZCMC2SOMD` | DEC | 17 |  | CA Set 2 Social Media |
| 67 | `F_ZCMC2MOB` | DEC | 17 |  | CA Set 2 Mobile |
| 68 | `F_ZCMC2TEL` | DEC | 17 |  | CA Set 2 Telephone |
| 69 | `F_ZCMC2MAIL` | DEC | 17 |  | CA Set 2 Mail |
| 70 | `F_ZCMB3TTL` | DEC | 17 |  | BP Set 3 Total Count |
| 71 | `F_ZCMB3SBTA` | DEC | 17 |  | BP Set 3 Sub Total A |
| 72 | `F_ZCMB3SBTB` | DEC | 17 |  | BP Set 3 Sub Total B |
| 73 | `F_ZCMB3EML` | DEC | 17 |  | BP Set 3 Email |
| 74 | `F_ZCMB3SMS` | DEC | 17 |  | BP Set 3 SMS |
| 75 | `F_ZCMB3WEB` | DEC | 17 |  | BP Set 3 Web |
| 76 | `F_ZCMB3SOMD` | DEC | 17 |  | BP Set 3 Social Media |
| 77 | `F_ZCMB3MOB` | DEC | 17 |  | BP Set 3 Mobile |
| 78 | `F_ZCMB3TEL` | DEC | 17 |  | BP Set 3 Telephone |
| 79 | `F_ZCMB3MAIL` | DEC | 17 |  | BP Set 3 Mail |
| 80 | `F_ZCMC3TTL` | DEC | 17 |  | CA Set 3 Total Count |
| 81 | `F_ZCMC3SBTA` | DEC | 17 |  | CA Set 3 Sub Total A |
| 82 | `F_ZCMC3SBTB` | DEC | 17 |  | CA Set 3 Sub Total B |
| 83 | `F_ZCMC3EML` | DEC | 17 |  | CA Set 3 Email |
| 84 | `F_ZCMC3SMS` | DEC | 17 |  | CA Set 3 SMS |
| 85 | `F_ZCMC3WEB` | DEC | 17 |  | CA Set 3 Web |
| 86 | `F_ZCMC3SOMD` | DEC | 17 |  | CA Set 3 Social Media |
| 87 | `F_ZCMC3MOB` | DEC | 17 |  | CA Set 3 Mobile |
| 88 | `F_ZCMC3TEL` | DEC | 17 |  | CA Set 3 Telephone |
| 89 | `F_ZCMC3MAIL` | DEC | 17 |  | CA Set 3 Mail |
| 90 | `F_OUCPREMIS` | CHAR | 10 |  | Premise |
| 91 | `F_ZCMSTRLBL` | CHAR | 3 |  | Segment Label - Strategic |
| 92 | `F_ZCMTSEWHQ` | NUMC | 5 |  | Total Sales EWH quantity |
| 93 | `F_ZCMTSICQ` | NUMC | 5 |  | Total Sales IC quantity |
| 94 | `F_ZCMTSACQ` | NUMC | 5 |  | Total Sales AC quantity |
| 95 | `F_ZCMTSEECQ` | NUMC | 5 |  | Total Sales EE&C quantity |
| 96 | `F_ZCMSEWHQ2` | NUMC | 5 |  | Sales EWH quantity (recent 2 yrs) |
| 97 | `F_ZCMSICQ2` | NUMC | 5 |  | Sales IC quantity (recent 2 yrs) |
| 98 | `F_ZCMSACQ2` | NUMC | 5 |  | Sales AC quantity (recent 2 yrs) |
| 99 | `F_ZCMSEECQ2` | NUMC | 5 |  | Sales EE&C quantity (recent 2 yrs) |
| 100 | `F_ZCMSEWHQ2T5` | NUMC | 5 |  | Sales EWH quantity (2-5 yrs ago) |
| 101 | `F_ZCMSICQ2T5` | NUMC | 5 |  | Sales IC quantity (2-5 yrs ago) |
| 102 | `F_ZCMSACQ2T5` | NUMC | 5 |  | Sales AC quantity (2-5 yrs ago) |
| 103 | `F_ZCMSEECQ2T5` | NUMC | 5 |  | Sales EE&C quantity (2-5 yrs ago) |
| 104 | `F_ZCMSEWHQ5T10` | NUMC | 5 |  | Sales EWH quantity (5-10 yrs ago) |
| 105 | `F_ZCMSICQ5T10` | NUMC | 5 |  | Sales IC quantity (5-10 yrs ago) |
| 106 | `F_ZCMSACQ5T10` | NUMC | 5 |  | Sales AC quantity (5-10 yrs ago) |
| 107 | `F_ZCMSEECQ5T10` | NUMC | 5 |  | Sales EE&C quantity (5-10 yrs ago) |
| 108 | `F_ZCMSEWHQ10` | NUMC | 5 |  | Sales EWH quantity (> 10 yrs ago) |
| 109 | `F_ZCMSICQ10` | NUMC | 5 |  | Sales IC quantity (> 10 yrs ago) |
| 110 | `F_ZCMSACQ10` | NUMC | 5 |  | Sales AC quantity (> 10 yrs ago) |
| 111 | `F_ZCMSEECQ10` | NUMC | 5 |  | Sales EE&C quantity (> 10 yrs ago) |
| 112 | `F_BP_CAT` | CHAR | 1 |  | Business Partner Category |
| 113 | `F_SMELABEL` | CHAR | 3 |  | Segment Label - SME |
| 114 | `F_PSYCHOGRAPHICLABEL` | CHAR | 16 |  | Segment Label V Psychographic |
| 115 | `F_CREDIT_SCORE` | DEC | 17 |  | Account Credit Score |
| 116 | `F_EECLABEL` | CHAR | 10 |  | EE&C Segment Label |
| 117 | `F_EEC_INDEX` | DEC | 10 |  | EE&C Participation Index |
| 118 | `F_CMBPLANE` | CHAR | 2 |  | 2-Character SAP Language Code |

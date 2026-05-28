# ZDFKKOP
**Description:** Items in contract account document
**Total Fields:** 190
**Key Fields:** MANDT, OPBEL, OPUPW, OPUPK, OPUPZ

## Programs Using This Table
- `zisbi0225`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `OPUPW` | NUMC | 3 | 🔑 | Repetition Item in Contract Account Document |
| 4 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 5 | `OPUPZ` | NUMC | 3 | 🔑 | Subitem for a Partial Clearing in Document |
| 6 | `BUKRS` | CHAR | 4 |  | Company Code |
| 7 | `GSBER` | CHAR | 4 |  | Business Area |
| 8 | `BUPLA` | CHAR | 4 |  | Business Place |
| 9 | `SEGMENT` | CHAR | 10 |  | Segment for Segmental Reporting |
| 10 | `PRCTR` | CHAR | 10 |  | Profit Center |
| 11 | `AUGST` | CHAR | 1 |  | Clearing status |
| 12 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 13 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 14 | `VTPOS` | NUMC | 6 |  | Contract: Item Number |
| 15 | `VTRE2` | CHAR | 20 |  | Additional Reference Information |
| 16 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 17 | `ABWBL` | CHAR | 12 |  | Number of the Substitute FI-CA Document |
| 18 | `ABWTP` | CHAR | 1 |  | Category of substitute document in FI-CA |
| 19 | `ABWKT` | CHAR | 12 |  | Alternative contract account for collective bills |
| 20 | `APPLK` | CHAR | 1 |  | Application area |
| 21 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 22 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 23 | `KOFIZ` | CHAR | 2 |  | Account Determination ID |
| 24 | `SPART` | CHAR | 2 |  | Division |
| 25 | `HKONT` | CHAR | 10 |  | General ledger account |
| 26 | `MWSKZ` | CHAR | 2 |  | Tax on Sales/Purchases Code |
| 27 | `MWSZKZ` | CHAR | 2 |  | Supplementary Tax |
| 28 | `XANZA` | CHAR | 1 |  | Item is a Down Payment/Down Payment Request |
| 29 | `STAKZ` | CHAR | 1 |  | Type of Statistical Line Item |
| 30 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 31 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 32 | `OPTXT` | CHAR | 50 |  | Item text |
| 33 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 34 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 35 | `FAEDS` | DATS | 8 |  | Due Date for Cash Discount |
| 36 | `VERKZ` | CHAR | 1 |  | Item Can Only Be Cleared |
| 37 | `STUDT` | DATS | 8 |  | Deferral to |
| 38 | `SKTPZ` | DEC | 5 |  | Cash Discount Percentage Rate |
| 39 | `XMANL` | CHAR | 1 |  | Exclude Item from Dunning Run |
| 40 | `KURSF` | DEC | 9 |  | Exchange rate |
| 41 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 42 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 43 | `BETR2` | CURR | 13 |  | Amount in second parallel currency with +/- sign |
| 44 | `BETR3` | CURR | 13 |  | Amount in third parallel currency with +/- sign |
| 45 | `SKFBT` | CURR | 13 |  | Amount eligible for cash discount in document currency |
| 46 | `SBETH` | CURR | 13 |  | Tax Amount in Local Currency With +/- Sign |
| 47 | `SBETW` | CURR | 13 |  | Tax Amount in Transaction Currency with +/- Sign |
| 48 | `SBET2` | CURR | 13 |  | Tax amount in second parallel currency |
| 49 | `SBET3` | CURR | 13 |  | Tax amount in third parallel currency |
| 50 | `MWSKO` | CHAR | 10 |  | Account for posting taxes for down payments |
| 51 | `MWVKO` | CHAR | 10 |  | Account for offsetting tax posting in down payments |
| 52 | `TXRUL` | CHAR | 1 |  | Update Rule for Tax and Tax Clearing |
| 53 | `SPZAH` | CHAR | 1 |  | Lock Reason for Automatic Payment |
| 54 | `PYMET` | CHAR | 1 |  | Payment Method |
| 55 | `PYBUK` | CHAR | 4 |  | Company Code for Automatic Payment Transactions |
| 56 | `PERNR` | NUMC | 8 |  | Personnel Number |
| 57 | `GRKEY` | CHAR | 3 |  | Grouping Key for Displaying Open Items |
| 58 | `PERSL` | CHAR | 4 |  | Key for Period Assignment |
| 59 | `XAESP` | CHAR | 1 |  | Printing - No Changes Possible |
| 60 | `AUGDT` | DATS | 8 |  | Clearing date |
| 61 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 62 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 63 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 64 | `AUGWA` | CUKY | 5 |  | Clearing currency |
| 65 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 66 | `AUGBS` | CURR | 13 |  | Tax amount in clearing currency |
| 67 | `AUGSK` | CURR | 13 |  | Cash Discount Granted/Surcharge Levied in Clearing Currency |
| 68 | `AUGVD` | DATS | 8 |  | Value date for clearing |
| 69 | `AUGOB` | CHAR | 1 |  | Item Canceled |
| 70 | `WHANG` | NUMC | 3 |  | Number of repetition items |
| 71 | `WHGRP` | NUMC | 3 |  | Repetition group |
| 72 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 73 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
| 74 | `MANSP` | CHAR | 1 |  | Dunning Lock Reason |
| 75 | `XAUGP` | CHAR | 1 |  | Check Sample Record Clearing |
| 76 | `ABRZU` | DATS | 8 |  | Lower Limit of Settlement Period |
| 77 | `ABRZO` | DATS | 8 |  | Upper Limit of the Billing Period |
| 78 | `FDGRP` | CHAR | 10 |  | Planning Group |
| 79 | `FDLEV` | CHAR | 2 |  | Planning level |
| 80 | `FDZTG` | NUMC | 2 |  | Additional Days for Cash Management |
| 81 | `FDWBT` | CURR | 13 |  | Planned Amount in Document or G/L Account Currency |
| 82 | `XTAUS` | CHAR | 1 |  | Item Split |
| 83 | `AUGRS` | CHAR | 1 |  | Clearing restriction |
| 84 | `PYGRP` | CHAR | 10 |  | Grouping field for automatic payments |
| 85 | `PDTYP` | CHAR | 1 |  | Category of Payment Specification |
| 86 | `SPERZ` | CHAR | 1 |  | Interest Lock Reason |
| 87 | `INFOZ` | NUMC | 3 |  | Doubtful Item Entry/Individual Value Adjustment |
| 88 | `TXJCD` | CHAR | 15 |  | Tax Jurisdiction |
| 89 | `TXDAT` | DATS | 8 |  | Decisive Date for Calculating Taxes |
| 90 | `VBUND` | CHAR | 6 |  | Company ID of trading partner |
| 91 | `KONTT` | CHAR | 2 |  | Account Assignment Category |
| 92 | `KONTL` | CHAR | 50 |  | Acct assnmnt string for industry-specific account assngments |
| 93 | `OPSTA` | CHAR | 3 |  | Dunning indicator |
| 94 | `BLART` | CHAR | 2 |  | Document Type |
| 95 | `EMGPA` | CHAR | 10 |  | Alternative Business Partner for Payments |
| 96 | `EMBVT` | CHAR | 4 |  | Bank Details ID of Payee |
| 97 | `EMADR` | CHAR | 10 |  | Address Number |
| 98 | `IKEY` | CHAR | 2 |  | Interest Key |
| 99 | `EUROU` | CHAR | 1 |  | Status of Euro Conversion |
| 100 | `XRAGL` | CHAR | 1 |  | Clearing posting reversed |
| 101 | `ASTKZ` | CHAR | 1 |  | Statistical Key of the Initiating Item |
| 102 | `ASBLG` | CHAR | 12 |  | Number of Triggering Document |
| 103 | `XBLNR` | CHAR | 16 |  | Reference Document Number |
| 104 | `INKPS` | NUMC | 3 |  | Collection Item |
| 105 | `RNDPS` | CHAR | 1 |  | Type of Rounding Item |
| 106 | `QSSKZ` | CHAR | 2 |  | Withholding Tax Code |
| 107 | `QSSEW` | CHAR | 2 |  | Withholding Tax Supplement |
| 108 | `QSPTP` | CHAR | 1 |  | Line Item Category From Withholding Tax View |
| 109 | `QSSHB` | CURR | 13 |  | Tax Base Amount |
| 110 | `QBSHB` | CURR | 13 |  | Withholding Tax Amount (in Document Currency) |
| 111 | `QSPRZ` | NUMC | 6 |  | Withholding Tax Percentage |
| 112 | `QSZNR` | CHAR | 10 |  | Certificate Number of the Withholding Tax Exemption |
| 113 | `XWHEX` | CHAR | 1 |  | Variable Withholding Tax in DFKKOPWH |
| 114 | `RFUPK` | NUMC | 4 |  | Reference Item In FI-CA Document |
| 115 | `STRKZ` | CHAR | 2 |  | Tax Code for Other Taxes |
| 116 | `FITPR` | CHAR | 2 |  | Tax type |
| 117 | `XPYOR` | CHAR | 1 |  | Item Included in a Payment Order |
| 118 | `LANDL` | CHAR | 3 |  | Country Supplied (for Tax Notifications) |
| 119 | `INTBU` | CHAR | 1 |  | Reason for Automatic Creation of Posting |
| 120 | `EMCRD` | CHAR | 6 |  | Alternative Payment Card ID in Document |
| 121 | `C4EYE` | CHAR | 2 |  | Check Reason for Workflows Acc. to Dual Control Principle |
| 122 | `C4EYP` | CHAR | 1 |  | Editing Process To Be Confirmed |
| 123 | `TXGRP` | CHAR | 6 |  | Grouping Key for Tax Items |
| 124 | `SCTAX` | CURR | 13 |  | Tax Portion in FI-CA Local Currency |
| 125 | `STTAX` | CURR | 13 |  | Tax Amount as Statistical Information in Document Currency |
| 126 | `STZAL` | CHAR | 1 |  | Status of Payment Processing |
| 127 | `ORUPZ` | CHAR | 3 |  | Subitem Number before Item Split |
| 128 | `NEGBU` | NUMC | 1 |  | Control Field for Negative Posting |
| 129 | `SUBAP` | CHAR | 1 |  | Subapplication in Contract Accounts Receivable and Payable |
| 130 | `PSWSL` | CUKY | 5 |  | Update Currency for General Ledger Transaction Figures |
| 131 | `PSWBT` | CURR | 13 |  | Amount for Updating in General Ledger |
| 132 | `PSWTX` | CURR | 13 |  | Tax Amount for Update in General Ledger |
| 133 | `PSGRP` | CHAR | 4 |  | Grouping Key for Document Items |
| 134 | `XCOLC` | CHAR | 1 |  | Item Is Included in Collection Case |
| 135 | `AASTA` | CHAR | 1 |  | Control Field for Account Assignment Distributions |
| 136 | `XCSHA` | CHAR | 1 |  | Document Contains Assignments from Cash Flows |
| 137 | `REACC` | CHAR | 10 |  | Originating Account in Cash Flow Anlaysis |
| 138 | `REBUK` | CHAR | 4 |  | Partner Company Code for Cash Flow Analysis |
| 139 | `XUSTPD` | CHAR | 1 |  | Tax on Sales/Purchases Was Calculated by Document |
| 140 | `PTITM` | CHAR | 1 |  | Status of Partner Settlement Using Billable Items |
| 141 | `EMMND` | NUMC | 6 |  | SEPA Mandate Identifier |
| 142 | `PALIX` | CHAR | 1 |  | Item Is Part of a Collaborative Liability |
| 143 | `.INCLUDE` | &nbsp; | 0 |  | Direct Debit Pre-Notification in Document Item |
| 144 | `PNNUM` | CHAR | 16 |  | SEPA: Number of Direct Debit Pre-Notification |
| 145 | `PNHKF` | CHAR | 2 |  | SEPA: Origin of Direct Debit Pre-Notification |
| 146 | `PNEXD` | DATS | 8 |  | SEPA: Date of Execution of Direct Debit Pre-Notifcation |
| 147 | `PNCTR` | CHAR | 1 |  | SEPA: Requirement for a Pre-Notification |
| 148 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Revenue Distribution |
| 149 | `FINRE` | CHAR | 12 |  | Contract Account of Final Recipient |
| 150 | `RDSTA` | CHAR | 1 |  | Current Distribution Status |
| 151 | `RDSTB` | CHAR | 1 |  | Last Distribution Status Reported |
| 152 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Factoring |
| 153 | `FASTA` | CHAR | 1 |  | Factoring: Current Status of Receivable |
| 154 | `PASTA` | CHAR | 1 |  | Factoring: Check Status for Clearing Information |
| 155 | `OPUPF` | NUMC | 3 |  | Subitems in Factoring |
| 156 | `.INCLUDE` | &nbsp; | 0 |  | Include: OI for Utility Companies: IS-U |
| 157 | `DEAKTIV` | CHAR | 12 |  | Deactivation of Budget Billing Plan via Invoicing |
| 158 | `SGRKEY` | NUMC | 3 |  | Grouping key for document items |
| 159 | `SOLLDAT` | DATS | 8 |  | Print date for BB requests or generation of partial bill |
| 160 | `RECPT` | CHAR | 10 |  | Business Partner That is to Receive the Amount |
| 161 | `TOCOLLECT` | CHAR | 1 |  | ID: |
| 162 | `EINMALANF` | CHAR | 1 |  | One-time request from budget billing plan |
| 163 | `VORAUSZAHL` | CHAR | 1 |  | Budget Billing Plan Item Is Advance Payment |
| 164 | `APERIODIC` | CHAR | 1 |  | Non-Periodic Posting |
| 165 | `ABRABS` | CHAR | 1 |  | Combine Budget Billing Amount Due Date and Bill |
| 166 | `GRBBP` | CHAR | 2 |  | Budget Billing: Grouping Key for Tax Determination Code |
| 167 | `ASMETH` | CHAR | 1 |  | Tax Determination Procedure |
| 168 | `INT_CROSSREFNO` | CHAR | 12 |  | IDE: internal cross reference number |
| 169 | `ETHPPM` | CHAR | 1 |  | Payment Process for Billing on Behalf of Third Parties |
| 170 | `PAYFREQID` | CHAR | 4 |  | Payment Frequency |
| 171 | `INVOICING_PARTY` | CHAR | 10 |  | Service Provider That Invoices the Contract |
| 172 | `PPMST` | CHAR | 1 |  | Status of Prepayment Meter Items (UK only) |
| 173 | `LOGNO` | CHAR | 3 |  | Line Number of Budget Billing Plan |
| 174 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 175 | `.INCLUDE` | &nbsp; | 0 |  | IS-T: Include open items for telecommunications companies |
| 176 | `APERIODICT` | CHAR | 1 |  | Non-Periodic Posting |
| 177 | `ADD_REFOBJ` | CHAR | 25 |  | Additional Reference Object |
| 178 | `ADD_REFOBJID` | CHAR | 2 |  | Additional Reference Object ID |
| 179 | `ADD_SERVICE` | CHAR | 3 |  | Type of Service |
| 180 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 181 | `.INCLUDE` | &nbsp; | 0 |  | Enhancement Structure for FPL9 |
| 182 | `ZZISSUEDATE` | DATS | 8 |  | Date of issue |
| 183 | `ZZBILLDUEDATE` | DATS | 8 |  | Bill Due Date |
| 184 | `ZZSMISTEXT` | CHAR | 50 |  | Indicator: updated by SMIS |
| 185 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 186 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 187 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 188 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 189 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 190 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |

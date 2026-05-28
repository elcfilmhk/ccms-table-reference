# ZIS_SFKKOP
**Description:** FI-CA: Data for displaying items in FI-CA document
**Total Fields:** 230
**Key Fields:** _none_

## Programs Using This Table
- `z_fkk_biw_get_data_simple=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `POTYP` | CHAR | 1 |  | Item category |
| 2 | `XMARK` | CHAR | 1 |  | Item selected |
| 3 | `.INCLUDE` | &nbsp; | 0 |  | Business Partner Items in Contract Account Document |
| 4 | `MANDT` | CLNT | 3 |  | Client |
| 5 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 6 | `OPUPW` | NUMC | 3 |  | Repetition Item in Contract Account Document |
| 7 | `OPUPK` | NUMC | 4 |  | Item number in contract account document |
| 8 | `OPUPZ` | NUMC | 3 |  | Subitem for a Partial Clearing in Document |
| 9 | `BUKRS` | CHAR | 4 |  | Company Code |
| 10 | `GSBER` | CHAR | 4 |  | Business Area |
| 11 | `BUPLA` | CHAR | 4 |  | Business Place |
| 12 | `SEGMENT` | CHAR | 10 |  | Segment for Segmental Reporting |
| 13 | `PRCTR` | CHAR | 10 |  | Profit Center |
| 14 | `AUGST` | CHAR | 1 |  | Clearing status |
| 15 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 16 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 17 | `VTPOS` | NUMC | 6 |  | Contract: Item Number |
| 18 | `VTRE2` | CHAR | 20 |  | Additional Reference Information |
| 19 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 20 | `ABWBL` | CHAR | 12 |  | Number of the Substitute FI-CA Document |
| 21 | `ABWTP` | CHAR | 1 |  | Category of substitute document in FI-CA |
| 22 | `ABWKT` | CHAR | 12 |  | Alternative contract account for collective bills |
| 23 | `APPLK` | CHAR | 1 |  | Application area |
| 24 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 25 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 26 | `KOFIZ` | CHAR | 2 |  | Account Determination ID |
| 27 | `SPART` | CHAR | 2 |  | Division |
| 28 | `HKONT` | CHAR | 10 |  | General ledger account |
| 29 | `MWSKZ` | CHAR | 2 |  | Tax on Sales/Purchases Code |
| 30 | `MWSZKZ` | CHAR | 2 |  | Supplementary Tax |
| 31 | `XANZA` | CHAR | 1 |  | Item is a Down Payment/Down Payment Request |
| 32 | `STAKZ` | CHAR | 1 |  | Type of Statistical Line Item |
| 33 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 34 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 35 | `OPTXT` | CHAR | 50 |  | Item text |
| 36 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 37 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 38 | `FAEDS` | DATS | 8 |  | Due Date for Cash Discount |
| 39 | `VERKZ` | CHAR | 1 |  | Item Can Only Be Cleared |
| 40 | `STUDT` | DATS | 8 |  | Deferral to |
| 41 | `SKTPZ` | DEC | 5 |  | Cash Discount Percentage Rate |
| 42 | `XMANL` | CHAR | 1 |  | Exclude Item from Dunning Run |
| 43 | `KURSF` | DEC | 9 |  | Exchange rate |
| 44 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 45 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 46 | `BETR2` | CURR | 13 |  | Amount in second parallel currency with +/- sign |
| 47 | `BETR3` | CURR | 13 |  | Amount in third parallel currency with +/- sign |
| 48 | `SKFBT` | CURR | 13 |  | Amount eligible for cash discount in document currency |
| 49 | `SBETH` | CURR | 13 |  | Tax Amount in Local Currency With +/- Sign |
| 50 | `SBETW` | CURR | 13 |  | Tax Amount in Transaction Currency with +/- Sign |
| 51 | `SBET2` | CURR | 13 |  | Tax amount in second parallel currency |
| 52 | `SBET3` | CURR | 13 |  | Tax amount in third parallel currency |
| 53 | `MWSKO` | CHAR | 10 |  | Account for posting taxes for down payments |
| 54 | `MWVKO` | CHAR | 10 |  | Account for offsetting tax posting in down payments |
| 55 | `TXRUL` | CHAR | 1 |  | Update Rule for Tax and Tax Clearing |
| 56 | `SPZAH` | CHAR | 1 |  | Lock Reason for Automatic Payment |
| 57 | `PYMET` | CHAR | 1 |  | Payment Method |
| 58 | `PYBUK` | CHAR | 4 |  | Company Code for Automatic Payment Transactions |
| 59 | `PERNR` | NUMC | 8 |  | Personnel Number |
| 60 | `GRKEY` | CHAR | 3 |  | Grouping Key for Displaying Open Items |
| 61 | `PERSL` | CHAR | 4 |  | Key for Period Assignment |
| 62 | `XAESP` | CHAR | 1 |  | Printing - No Changes Possible |
| 63 | `AUGDT` | DATS | 8 |  | Clearing date |
| 64 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 65 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 66 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 67 | `AUGWA` | CUKY | 5 |  | Clearing currency |
| 68 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 69 | `AUGBS` | CURR | 13 |  | Tax amount in clearing currency |
| 70 | `AUGSK` | CURR | 13 |  | Cash Discount Granted/Surcharge Levied in Clearing Currency |
| 71 | `AUGVD` | DATS | 8 |  | Value date for clearing |
| 72 | `AUGOB` | CHAR | 1 |  | Item Canceled |
| 73 | `WHANG` | NUMC | 3 |  | Number of repetition items |
| 74 | `WHGRP` | NUMC | 3 |  | Repetition group |
| 75 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 76 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
| 77 | `MANSP` | CHAR | 1 |  | Dunning Lock Reason |
| 78 | `XAUGP` | CHAR | 1 |  | Check Sample Record Clearing |
| 79 | `ABRZU` | DATS | 8 |  | Lower Limit of Settlement Period |
| 80 | `ABRZO` | DATS | 8 |  | Upper Limit of the Billing Period |
| 81 | `FDGRP` | CHAR | 10 |  | Planning Group |
| 82 | `FDLEV` | CHAR | 2 |  | Planning level |
| 83 | `FDZTG` | NUMC | 2 |  | Additional Days for Cash Management |
| 84 | `FDWBT` | CURR | 13 |  | Planned Amount in Document or G/L Account Currency |
| 85 | `XTAUS` | CHAR | 1 |  | Item Split |
| 86 | `AUGRS` | CHAR | 1 |  | Clearing restriction |
| 87 | `PYGRP` | CHAR | 10 |  | Grouping field for automatic payments |
| 88 | `PDTYP` | CHAR | 1 |  | Category of Payment Specification |
| 89 | `SPERZ` | CHAR | 1 |  | Interest Lock Reason |
| 90 | `INFOZ` | NUMC | 3 |  | Doubtful Item Entry/Individual Value Adjustment |
| 91 | `TXJCD` | CHAR | 15 |  | Tax Jurisdiction |
| 92 | `TXDAT` | DATS | 8 |  | Decisive Date for Calculating Taxes |
| 93 | `VBUND` | CHAR | 6 |  | Company ID of trading partner |
| 94 | `KONTT` | CHAR | 2 |  | Account Assignment Category |
| 95 | `KONTL` | CHAR | 50 |  | Acct assnmnt string for industry-specific account assngments |
| 96 | `OPSTA` | CHAR | 3 |  | Dunning indicator |
| 97 | `BLART` | CHAR | 2 |  | Document Type |
| 98 | `EMGPA` | CHAR | 10 |  | Alternative Business Partner for Payments |
| 99 | `EMBVT` | CHAR | 4 |  | Bank Details ID of Payee |
| 100 | `EMADR` | CHAR | 10 |  | Address Number |
| 101 | `IKEY` | CHAR | 2 |  | Interest Key |
| 102 | `EUROU` | CHAR | 1 |  | Status of Euro Conversion |
| 103 | `XRAGL` | CHAR | 1 |  | Clearing posting reversed |
| 104 | `XWHPO` | CHAR | 1 |  | Expanded Repetition Item |
| 105 | `ASTKZ` | CHAR | 1 |  | Statistical Key of the Initiating Item |
| 106 | `ASBLG` | CHAR | 12 |  | Number of Triggering Document |
| 107 | `XBLNR` | CHAR | 16 |  | Reference Document Number |
| 108 | `INKPS` | NUMC | 3 |  | Collection Item |
| 109 | `RNDPS` | CHAR | 1 |  | Type of Rounding Item |
| 110 | `QSSKZ` | CHAR | 2 |  | Withholding Tax Code |
| 111 | `QSSEW` | CHAR | 2 |  | Withholding Tax Supplement |
| 112 | `QSPTP` | CHAR | 1 |  | Line Item Category From Withholding Tax View |
| 113 | `QSSHB` | CURR | 13 |  | Tax Base Amount |
| 114 | `QBSHB` | CURR | 13 |  | Withholding Tax Amount (in Document Currency) |
| 115 | `QSPRZ` | NUMC | 6 |  | Withholding Tax Percentage |
| 116 | `QSZNR` | CHAR | 10 |  | Certificate Number of the Withholding Tax Exemption |
| 117 | `XWHEX` | CHAR | 1 |  | Variable Withholding Tax in DFKKOPWH |
| 118 | `RFUPK` | NUMC | 4 |  | Reference Item In FI-CA Document |
| 119 | `STRKZ` | CHAR | 2 |  | Tax Code for Other Taxes |
| 120 | `FITPR` | CHAR | 2 |  | Tax type |
| 121 | `XPYOR` | CHAR | 1 |  | Item Included in a Payment Order |
| 122 | `LANDL` | CHAR | 3 |  | Country Supplied (for Tax Notifications) |
| 123 | `INTBU` | CHAR | 1 |  | Reason for Automatic Creation of Posting |
| 124 | `EMCRD` | CHAR | 6 |  | Alternative Payment Card ID in Document |
| 125 | `C4EYE` | CHAR | 2 |  | Check Reason for Workflows Acc. to Dual Control Principle |
| 126 | `CFOPN` | CHAR | 10 |  | CFOP Code and Extension |
| 127 | `C4EYP` | CHAR | 1 |  | Editing Process To Be Confirmed |
| 128 | `TXGRP` | CHAR | 6 |  | Grouping Key for Tax Items |
| 129 | `SCTAX` | CURR | 13 |  | Tax Portion in FI-CA Local Currency |
| 130 | `STTAX` | CURR | 13 |  | Tax Amount as Statistical Information in Document Currency |
| 131 | `STZAL` | CHAR | 1 |  | Status of Payment Processing |
| 132 | `ORUPZ` | CHAR | 3 |  | Subitem Number before Item Split |
| 133 | `NEGBU` | NUMC | 1 |  | Control Field for Negative Posting |
| 134 | `SUBAP` | CHAR | 1 |  | Subapplication in Contract Accounts Receivable and Payable |
| 135 | `PSWSL` | CUKY | 5 |  | Update Currency for General Ledger Transaction Figures |
| 136 | `PSWBT` | CURR | 13 |  | Amount for Updating in General Ledger |
| 137 | `PSWTX` | CURR | 13 |  | Tax Amount for Update in General Ledger |
| 138 | `PSGRP` | CHAR | 4 |  | Grouping Key for Document Items |
| 139 | `XCOLC` | CHAR | 1 |  | Item Is Included in Collection Case |
| 140 | `AASTA` | CHAR | 1 |  | Control Field for Account Assignment Distributions |
| 141 | `XCSHA` | CHAR | 1 |  | Document Contains Assignments from Cash Flows |
| 142 | `REACC` | CHAR | 10 |  | Originating Account in Cash Flow Anlaysis |
| 143 | `REBUK` | CHAR | 4 |  | Partner Company Code for Cash Flow Analysis |
| 144 | `XUSTPD` | CHAR | 1 |  | Tax on Sales/Purchases Was Calculated by Document |
| 145 | `PTITM` | CHAR | 1 |  | Status of Partner Settlement Using Billable Items |
| 146 | `EMMND` | NUMC | 6 |  | SEPA Mandate Identifier |
| 147 | `PALIX` | CHAR | 1 |  | Item Is Part of a Collaborative Liability |
| 148 | `CLRLOCK` | CHAR | 1 |  | Clearing Lock Reason |
| 149 | `.INCLUDE` | &nbsp; | 0 |  | Direct Debit Pre-Notification in Document Item |
| 150 | `PNNUM` | CHAR | 16 |  | SEPA: Number of Direct Debit Pre-Notification |
| 151 | `PNHKF` | CHAR | 2 |  | SEPA: Origin of Direct Debit Pre-Notification |
| 152 | `PNEXD` | DATS | 8 |  | SEPA: Date of Execution of Direct Debit Pre-Notifcation |
| 153 | `PNCTR` | CHAR | 1 |  | SEPA: Requirement for a Pre-Notification |
| 154 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Revenue Distribution |
| 155 | `FINRE` | CHAR | 12 |  | Contract Account of Final Recipient |
| 156 | `RDSTA` | CHAR | 1 |  | Current Distribution Status |
| 157 | `RDSTB` | CHAR | 1 |  | Last Distribution Status Reported |
| 158 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Factoring |
| 159 | `FASTA` | CHAR | 1 |  | Factoring: Current Status of Receivable |
| 160 | `PASTA` | CHAR | 1 |  | Factoring: Check Status for Clearing Information |
| 161 | `OPUPF` | NUMC | 3 |  | Subitems in Factoring |
| 162 | `.INCLUDE` | &nbsp; | 0 |  | FM Account Assignments for FI-CA Including Type |
| 163 | `FMTYP` | CHAR | 2 |  | Update Method for FM - FI-CA Integration |
| 164 | `.INCLUDE` | &nbsp; | 0 |  | Funds Management Account Assignments for FI-CA |
| 165 | `ORIGFIKRS` | CHAR | 4 |  | Original FM Area for FM Account Assignment |
| 166 | `FIPEX` | CHAR | 24 |  | Commitment item |
| 167 | `FISTL` | CHAR | 16 |  | Funds Center |
| 168 | `FONDS` | CHAR | 10 |  | Fund |
| 169 | `FKBER` | CHAR | 16 |  | Functional Area |
| 170 | `MEASURE` | CHAR | 24 |  | Funded Program |
| 171 | `GRANT_NBR` | CHAR | 20 |  | Grant |
| 172 | `BUDGETYEAR` | NUMC | 4 |  | Original Year for FM Account Assignment |
| 173 | `BUDGET_PD` | CHAR | 10 |  | FM: Budget Period |
| 174 | `.INCLUDE` | &nbsp; | 0 |  | Include: OI for Utility Companies: IS-U |
| 175 | `DEAKTIV` | CHAR | 12 |  | Deactivation of Budget Billing Plan via Invoicing |
| 176 | `SGRKEY` | NUMC | 3 |  | Grouping key for document items |
| 177 | `SOLLDAT` | DATS | 8 |  | Print date for BB requests or generation of partial bill |
| 178 | `RECPT` | CHAR | 10 |  | Business Partner That is to Receive the Amount |
| 179 | `TOCOLLECT` | CHAR | 1 |  | ID: |
| 180 | `EINMALANF` | CHAR | 1 |  | One-time request from budget billing plan |
| 181 | `VORAUSZAHL` | CHAR | 1 |  | Budget Billing Plan Item Is Advance Payment |
| 182 | `APERIODIC` | CHAR | 1 |  | Non-Periodic Posting |
| 183 | `ABRABS` | CHAR | 1 |  | Combine Budget Billing Amount Due Date and Bill |
| 184 | `GRBBP` | CHAR | 2 |  | Budget Billing: Grouping Key for Tax Determination Code |
| 185 | `ASMETH` | CHAR | 1 |  | Tax Determination Procedure |
| 186 | `INT_CROSSREFNO` | CHAR | 12 |  | IDE: internal cross reference number |
| 187 | `ETHPPM` | CHAR | 1 |  | Payment Process for Billing on Behalf of Third Parties |
| 188 | `PAYFREQID` | CHAR | 4 |  | Payment Frequency |
| 189 | `INVOICING_PARTY` | CHAR | 10 |  | Service Provider That Invoices the Contract |
| 190 | `PPMST` | CHAR | 1 |  | Status of Prepayment Meter Items (UK only) |
| 191 | `LOGNO` | CHAR | 3 |  | Line Number of Budget Billing Plan |
| 192 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 193 | `.INCLUDE` | &nbsp; | 0 |  | IS-T: Include open items for telecommunications companies |
| 194 | `APERIODICT` | CHAR | 1 |  | Non-Periodic Posting |
| 195 | `ADD_REFOBJ` | CHAR | 25 |  | Additional Reference Object |
| 196 | `ADD_REFOBJID` | CHAR | 2 |  | Additional Reference Object ID |
| 197 | `ADD_SERVICE` | CHAR | 3 |  | Type of Service |
| 198 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 199 | `.INCLUDE` | &nbsp; | 0 |  | Enhancement Structure for FPL9 |
| 200 | `ZZISSUEDATE` | DATS | 8 |  | Date of issue |
| 201 | `ZZBILLDUEDATE` | DATS | 8 |  | Bill Due Date |
| 202 | `ZZSMISTEXT` | CHAR | 50 |  | Indicator: updated by SMIS |
| 203 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 204 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 205 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 206 | `INTTX` | CHAR | 1 |  | Internal Tax Characteristic for Tax Handling |
| 207 | `.INCLUDE` | &nbsp; | 0 |  | KKK: Open amounts to display items in KK document |
| 208 | `BETRO` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 209 | `BETRHO` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 210 | `BETR2O` | CURR | 13 |  | Amount in second parallel currency with +/- sign |
| 211 | `BETR3O` | CURR | 13 |  | Amount in third parallel currency with +/- sign |
| 212 | `SBETHO` | CURR | 13 |  | Tax Amount in Local Currency With +/- Sign |
| 213 | `SBETWO` | CURR | 13 |  | Tax Amount in Transaction Currency with +/- Sign |
| 214 | `SBET2O` | CURR | 13 |  | Tax amount in second parallel currency |
| 215 | `SBET3O` | CURR | 13 |  | Tax amount in third parallel currency |
| 216 | `MAHNDAT` | DATS | 8 |  | Date of issue |
| 217 | `MAHNS` | NUMC | 2 |  | Dunning Level |
| 218 | `MSTYP` | CHAR | 2 |  | Dunning Level Category |
| 219 | `MBETM` | CURR | 13 |  | Dunned amount in transaction currency |
| 220 | `MAHNV_MAZE` | CHAR | 2 |  | Dunning Procedure |
| 221 | `CLBLK` | CHAR | 1 |  | Clearing Lock |
| 222 | `.INCLUDE` | &nbsp; | 0 |  | IS-U Include for Data to Display Items in Document |
| 223 | `DISCNO` | CHAR | 12 |  | Disconnection document number |
| 224 | `STPRZ` | CHAR | 8 |  | Tax rate in output format |
| 225 | `PRINTDOC_PP` | CHAR | 12 |  | Print Document for a Payment Plan Item |
| 226 | `PRDOC_PP_BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 227 | `RLOCK` | CHAR | 30 |  | Icon For Lock (Interest, Dunning and Payment Lock) |
| 228 | `PRINTDOC_BBP` | CHAR | 12 |  | Print Document Number for Budget Billing Item |
| 229 | `PRDOC_BBP_BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 230 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |

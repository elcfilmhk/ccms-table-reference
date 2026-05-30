# `DFKKRH`

**Description:** Payment Request History — historical payment request
**Category:** Standard SAP Table
**References:** 7 SELECT statements across 4 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkrh/) — validated 2026-05-30, schema v1.0
**Schema fields:** 69 fields | **Data types:** CHAR(41), CUKY(1), CURR(10), DATS(5), INT4(8), NUMC(4)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KEYR1` | KEYR1_KK | — | CHAR | 12 | 0 | Returns Lot |
| `POSRA` | POSRA_KK | — | NUMC | 6 | 0 | Item number in a returns lot |
| `OPBEL` | OPBEL_KK | — | CHAR | 12 | 0 | Number of Contract Accts Rec. &amp; Payable Doc. |
| `URBEL` | URBEL_KK | — | CHAR | 12 | 0 | Document Number of Receivables Document |
| `BETRWR` | BETRWR_KK | — | CURR | 13 | 2 | Partial Amount Of Return |
| `BETRR` | BETRR_KK | — | CURR | 13 | 2 | Return amount |
| `BTRB1` | BTRB1_KK | — | CURR | 13 | 2 | Charge amount from bank 1 |
| `BTRB2` | BTRB2_KK | — | CURR | 13 | 2 | Charge amount from bank 2 |
| `STBB1` | STBB1_KK | — | CURR | 13 | 2 | Tax Amount: Bank Charge 1 |
| `STBB2` | STBB2_KK | — | CURR | 13 | 2 | Tax amount: Bank charge 2 |
| `BTRV1` | BTRV1_KK | — | CURR | 13 | 2 | Returns Charge 1 |
| `BTRV2` | BTRV2_KK | — | CURR | 13 | 2 | Return charge 2 |
| `STBV1` | STBV1_KK | — | CURR | 13 | 2 | Tax amount: Return charges 1 |
| `STBV2` | STBV2_KK | — | CURR | 13 | 2 | Tax amount: Return charges 2 |
| `WAERS` | WAERS | — | CUKY | 5 | 0 | Currency Key |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `RLGRD` | RLGRD_KK | — | CHAR | 3 | 0 | Return reason |
| `BANKL` | GPBANKS | — | CHAR | 3 | 0 | Banking Country of Business Partner |
| `BANKK` | GPBANKK | — | CHAR | 15 | 0 | Business Partner Bank Number |
| `BANKN` | GPBANKN | — | CHAR | 18 | 0 | Account Number of Business Partner |
| `IBAN` | IBAN | — | CHAR | 34 | 0 | IBAN (International Bank Account Number) |
| `CHECF` | CHECF_KK | — | CHAR | 16 | 0 | Number of a returned check |
| `NRZAS` | NRZAS_KK | — | CHAR | 12 | 0 | Payment Form Number |
| `HBKID` | HBKID | — | CHAR | 5 | 0 | Short Key for a House Bank |
| `HKTID` | HKTID | — | CHAR | 5 | 0 | ID for account details |
| `RLMOD` | RLMOD_KK | — | CHAR | 1 | 0 | Returns Posting Type |
| `STODT` | STODT_KK | — | DATS | 8 | 0 | Reversal Document Posting Date |
| `STBLG` | STBLG_KK | — | CHAR | 12 | 0 | Number of Reverse Document/Reset Document |
| `XSTOR` | XSTOR_KK | — | CHAR | 1 | 0 | Document Has Been Reversed |
| `RLANZ` | RLANZ_KK | — | NUMC | 2 | 0 | Number Of Returns That Occurred in The Observation Period |
| `BONIT` | BONIT_KK | — | NUMC | 4 | 0 | Creditworthiness |
| `TOGRU` | TOGRU_KK | — | CHAR | 4 | 0 | Tolerance group for contract account |
| `XGEBV` | XGEBV_KK | — | CHAR | 1 | 0 | Pass On Bank Charges |
| `XGEBS` | XGEBS_KK | — | CHAR | 1 | 0 | Calculate Graduated Charges |
| `XEZSP` | XEZSP_KK | — | CHAR | 1 | 0 | Field is obsolete |
| `XEZSB` | XEZSB_KK | — | CHAR | 1 | 0 | Field is obsolete |
| `XBVBL` | XBVBL_KK | — | CHAR | 1 | 0 | Delete bank details |
| `STUNT` | STUNT_KK | — | NUMC | 3 | 0 | Deferral days |
| `STUDT` | STUDT_KK | — | DATS | 8 | 0 | Deferral to |
| `MSPOP` | MSPOP_KK | — | CHAR | 1 | 0 | Dunning Lock Reason for Line Item |
| `MSPOP_DAYS` | MSPOP_DAYS_KK | — | INT4 | 10 | 0 | Item dunning lock: days |
| `PSPOP` | PSPOP_KK | — | CHAR | 1 | 0 | Payment lock reason for item |
| `PSPOP_DAYS` | PSPOP_DAYS_KK | — | INT4 | 10 | 0 | Payment lock for incoming payments: Duration in days |
| `MSPKO` | MSPKO_KK | — | CHAR | 1 | 0 | Dunning lock reason for contract account |
| `MSPKO_DAYS` | MSPKO_DAYS_KK | — | INT4 | 10 | 0 | Contract acct dunn. lock: days |
| `EZSKO` | EZSKO_KK | — | CHAR | 1 | 0 | Reason for Lock on Incoming Payment for Contract Account |
| `EZSKO_DAYS` | EZSKO_DAYS_KK | — | INT4 | 10 | 0 | Contract account incoming payment lock: Duration in days |
| `AZSKO` | AZSKO_KK | — | CHAR | 1 | 0 | Reason for Outgoing Payment Lock for Contract Account |
| `AZSKO_DAYS` | AZSKO_DAYS_KK | — | INT4 | 10 | 0 | Contract account outgoing payments lock: Duration in days |
| `EZAWE` | EZAWE_KK | — | CHAR | 1 | 0 | Incoming Payment Method |
| `GEBST` | GEBST_KK | — | CHAR | 1 | 0 | Post Charges Statistically |
| `XDELEZAWE` | XDELEZAWE_KK | — | CHAR | 1 | 0 | Delete payment method with account instead of changing |
| `XDELAZAWE` | XDELAZAWE_KK | — | CHAR | 1 | 0 | Returns Activity: Delete Outgoing Payment Method in Account |
| `MACHG` | MACHG_KK | — | CHAR | 1 | 0 | Activate Event for Changing Master Data |
| `BSNTE` | BSNTE_KK | — | CHAR | 1 | 0 | Inform Specialist |
| `BCORR` | BCORR_KK | — | CHAR | 1 | 0 | Activate Event for Creating Correspondence |
| `EZVTG` | EZVTG_KK | — | CHAR | 1 | 0 | Incoming Payment Lock in Contract |
| `EZVTG_DAYS` | EZVTG_DAYS_KK | — | INT4 | 10 | 0 | Incoming Payment Lock in Contract: Duration in Days |
| `AZVTG` | AZVTG_KK | — | CHAR | 1 | 0 | Outgoing Payment Lock Reason for Contract |
| `AZVTG_DAYS` | AZVTG_DAYS_KK | — | INT4 | 10 | 0 | Outgoing Payment Lock Contract: Duration in Days |
| `MSVTG` | MSVTG_KK | — | CHAR | 1 | 0 | Dunning Lock Reason for Contract |
| `MSVTG_DAYS` | MSVTG_DAYS_KK | — | INT4 | 10 | 0 | Dunning Lock in Contract: Duration in Days |
| `XDELPZAWE` | XDELPZAWE_KK | — | CHAR | 1 | 0 | Delete Payment Method in Item |
| `XCORPZAWE` | XCORPZAWE_KK | — | CHAR | 1 | 0 | Change Pymt Meth. in Item |
| `VERSN` | VERSN_KK | — | CHAR | 3 | 0 | Version Number |
| `INFCON` | INFCON_KK | — | CHAR | 1 | 0 | Write Entry in Information Container |
| `SWIFT` | SWIFT | — | CHAR | 11 | 0 | SWIFT/BIC for International Payments |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | DFKKRH | MANDT | T000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisfi0039.txt`
- `zisfi0088.txt`
- `zisfi0097.txt`
- `zisfi0131.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
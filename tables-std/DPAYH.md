# `DPAYH`

**Description:** Direct Debit Header — DD payment batch header
**Category:** Standard SAP Table
**References:** 87 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dpayh/) — validated 2026-05-30, schema v1.0
**Schema fields:** 97 fields | **Data types:** CHAR(76), CUKY(1), CURR(9), DATS(4), DEC(2), INT4(1), LANG(1), NUMC(1), RAW(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `GRPNO` | GRPNO_PAY | — | INT4 | 10 | 0 | Grouping criterium for payments |
| `PMF_KEY` | PMFKEY_PAY | — | CHAR | 15 | 0 | Redundant Key for Payment Medium Print |
| `SRTF1` | SRTF1_PAY | — | CHAR | 20 | 0 | Format-specific sorting of payment data |
| `SRTF2` | SRTF2_PAY | — | CHAR | 48 | 0 | User-defined sorting of payment data |
| `XAVIS` | XAVIS_PAY | — | CHAR | 1 | 0 | Output payment advice |
| `ORG1T` | ORG1T_PAY | — | CHAR | 2 | 0 | Type of Organization |
| `ORG1R` | ORG1R_PAY | — | CHAR | 8 | 0 | Reference for Organization |
| `ORG2T` | ORG2T_PAY | — | CHAR | 2 | 0 | Type of organization for which the payment is made |
| `ORG2R` | ORG2R_PAY | — | CHAR | 8 | 0 | Reference to the Organization for Which the Payment is Made |
| `GPA1T` | GPA1T_PAY | — | CHAR | 2 | 0 | Business Partner Category |
| `GPA1R` | GPA1R_PAY | — | CHAR | 12 | 0 | Business Partner Reference |
| `ACC1T` | ACC1T_PAY | — | CHAR | 2 | 0 | Contract Account Category |
| `ACC1R` | ACC1R_PAY | — | CHAR | 18 | 0 | Reference to Contract Account |
| `DOC1T` | DOC1T_PAY | — | CHAR | 2 | 0 | Payment document category |
| `DOC1R` | DOC1R_PAY | — | CHAR | 24 | 0 | Reference to Payment Document |
| `MASTT` | MASTT_KK | — | CHAR | 2 | 0 | Master record type for payment items |
| `MASTR` | MASTR_KK | — | CHAR | 20 | 0 | Master Record Reference for Payment Item |
| `ZADNR` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `ZNME1` | NAMEZ_KK | — | CHAR | 40 | 0 | Name of the Payee |
| `ZNME2` | NAMEZ_KK | — | CHAR | 40 | 0 | Name of the Payee |
| `ZSPRA` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `ZLAND` | LAND1 | T005 | CHAR | 3 | 0 | Country Key |
| `ZREGI` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `ZORT1` | AD_CITY1 | — | CHAR | 40 | 0 | City |
| `ZORT2` | AD_CITY2 | — | CHAR | 40 | 0 | District |
| `ZORTP` | AD_POBXLOC | — | CHAR | 40 | 0 | PO Box city |
| `ZPST1` | AD_PSTCD1 | — | CHAR | 10 | 0 | City postal code |
| `ZPST2` | AD_PSTCD2 | — | CHAR | 10 | 0 | PO Box Postal Code |
| `ZPST3` | AD_PSTCD3 | — | CHAR | 10 | 0 | Company Postal Code (for Large Customers) |
| `ZPFAC` | AD_POBX | — | CHAR | 10 | 0 | PO Box |
| `ZSTRA` | AD_STREET | — | CHAR | 60 | 0 | Street |
| `ZSTR1` | AD_HSNM1 | — | CHAR | 10 | 0 | House Number |
| `ZSTR2` | AD_HSNM2 | — | CHAR | 10 | 0 | House number supplement |
| `ZTEL1` | AD_TLNMBR | — | CHAR | 30 | 0 | Telephone no.: dialling code+number |
| `ZTEL2` | AD_TLXTNS | — | CHAR | 10 | 0 | Telephone no.: Extension |
| `ZFAX1` | AD_FXNMBR | — | CHAR | 30 | 0 | Fax number: dialling code+number |
| `ZFAX2` | AD_FXXTNS | — | CHAR | 10 | 0 | Fax no.: Extension |
| `ZBNKS` | BANKS | T005 | CHAR | 3 | 0 | Bank country key |
| `ZBNKY` | DZBNKY | — | CHAR | 15 | 0 | Bank key of the payee&#039;s bank |
| `ZBNKL` | DZBNKL | — | CHAR | 15 | 0 | Bank number of the payee&#039;s bank |
| `ZSWIF` | SWIFT | — | CHAR | 11 | 0 | SWIFT/BIC for International Payments |
| `ZBNKN` | DZBNKN | — | CHAR | 18 | 0 | Bank account number of the payee |
| `ZBKON` | DZBKON | — | CHAR | 2 | 0 | Bank Control Key of the Payee&#039;s Bank |
| `ZBKRF` | BKREF | — | CHAR | 20 | 0 | Reference specifications for bank details |
| `ZBKIN` | KOINH_KK | — | CHAR | 60 | 0 | Name of Holder of Bank Account/Check Issuer/Cardholder |
| `BBUKR` | BUKRS_PAY | T001 | CHAR | 4 | 0 | Company Code in Payment Document |
| `BGSBR` | GSBER_PAY | TGSB | CHAR | 4 | 0 | Business area in payment document |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `RBETR` | RBETR | — | CURR | 13 | 2 | Amount in Local Currency |
| `RWBTR` | RWBTR | — | CURR | 13 | 2 | Amount Paid in the Payment Currency |
| `RSKON` | RSKON | — | CURR | 13 | 2 | Total Cash Discount for the Payment Trans. (Local Currency) |
| `RWSKT` | RWSKT | — | CURR | 13 | 2 | Total Cash Discount for the Pmnt Transactn in Pmnt Currency |
| `ZALDT` | DZALDT_ZHL | — | DATS | 8 | 0 | Posting date of the payment document |
| `DIFFB` | DIFFB_KK | — | CURR | 13 | 2 | Difference Amount in Clearing Processing |
| `AUSFD` | AUSFD | — | DATS | 8 | 0 | Due date of the paid items |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `RZAWE` | PYMET_KK | TFK042Z | CHAR | 1 | 0 | Payment Method |
| `UZAWE` | UZAWE | T042F | CHAR | 2 | 0 | Payment Method Supplement |
| `AVISG` | AVISG | — | CHAR | 1 | 0 | Reason for Printing Payment Advice |
| `RPOST` | RPOST | — | DEC | 5 | 0 | Number of Items Paid |
| `RTEXT` | RTEXT_D | — | DEC | 5 | 0 | Number of Text Lines for the Items Paid |
| `PYGRP` | PYGRP_KK | — | CHAR | 10 | 0 | Grouping field for automatic payments |
| `PAYGR` | PAYGR_PAY | — | CHAR | 50 | 0 | Generated grouping field in payments |
| `EIGBV` | EIGBV_KK | — | CHAR | 25 | 0 | Own Bank Details |
| `HBKID` | HBKID | T012 | CHAR | 5 | 0 | Short Key for a House Bank |
| `HKTID` | HKTID | T012K | CHAR | 5 | 0 | ID for account details |
| `UBNKS` | BANKS | T005 | CHAR | 3 | 0 | Bank country key |
| `UBNKY` | UBNKY | — | CHAR | 15 | 0 | Bank key of our bank |
| `UBNKL` | UBNKL | — | CHAR | 15 | 0 | Bank number of our bank |
| `UBKNT` | UBKNT | — | CHAR | 18 | 0 | Our account number at the bank |
| `UBKON` | UBKON | — | CHAR | 2 | 0 | Bank control key at our bank |
| `UBHKT` | UBHKT | SKA1 | CHAR | 10 | 0 | G/L Account Number for Our Bank Account / Bank Sub-Account |
| `DTAWS` | DTAWS | TFK015W | CHAR | 2 | 0 | Instruction key for data medium exchange |
| `DTAMS` | DTAMS | — | CHAR | 1 | 0 | Indicator for Data Medium Exchange |
| `TXTSL` | TXTSL_042Z | — | CHAR | 2 | 0 | Text key for the code line on the form |
| `TXERG` | TXERG | — | CHAR | 3 | 0 | Text key supplement |
| `CCINS` | CC_INSTITUTE | TB033 | CHAR | 4 | 0 | Payment card type |
| `CCNUM` | CCNUM | — | CHAR | 25 | 0 | Payment cards: Card number |
| `RQSTW` | RQSTW | — | CURR | 13 | 2 | Withholding Tax In Payment Currency (Credit-Side) |
| `RQSTH` | RQSTH | — | CURR | 13 | 2 | Withholding Tax In Local Currency (Credit-Side) |
| `RQSEW` | RQSEW | — | CURR | 13 | 2 | Withholding Tax In Payment Currency (Debit-Side) |
| `RQSEH` | RQSEH | — | CURR | 13 | 2 | Withholding Tax In Local Currency (Debit-Side) |
| `ORIBD` | ORIBD_KK | — | CHAR | 1 | 0 | Payment Program: Origin of Business Partner Bank Data |
| `XNOLC` | XNOLC_KK | — | CHAR | 1 | 0 | Payment Program: Local Currency Amounts Incomplete |
| `ZIBAN` | IBAN | — | CHAR | 34 | 0 | IBAN (International Bank Account Number) |
| `PDKEY` | PDKEY_KK | — | NUMC | 12 | 0 | Number of Payment Specification |
| `PDREF` | PDREF_KK | — | CHAR | 16 | 0 | Reference Number of Payment Specification |
| `PPKEY` | PPKEY_KK | — | CHAR | 12 | 0 | Identification of Promise to Pay |
| `PRDAT` | PRODT_KK | — | DATS | 8 | 0 | Payment Date Promised |
| `MGUID` | GUID16 | — | RAW | 16 | 0 | Generic Data Element for GUID Fields (X16) |
| `CGUID` | CARD_GUID | — | RAW | 16 | 0 | GUID of a Payment Card |
| `ENCTP` | CCSECA_ENCTYPE | — | CHAR | 1 | 0 | Type of Encryption |
| `PAY_TYPE` | SEPA_PAY_TYPE | — | CHAR | 1 | 0 | SEPA: Transaction Type |
| `SEQ_TYPE` | SEPA_SEQ_TYPE | — | CHAR | 4 | 0 | SEPA: Sequence Type |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |
| `B2B` | SEPA_B2B | — | CHAR | 1 | 0 | SEPA-Mandate: B2B Mandate |
| `INST_CODE` | FSEPA_INST_CODE | — | CHAR | 4 | 0 | Local Instrument Code (Direct Debit Type) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BBUKR` | SYST | MANDT | T001 |  | |
| `BBUKR` | DPAYH | BBUKR | T001 |  | |
| `BGSBR` | SYST | MANDT | TGSB |  | |
| `BGSBR` | DPAYH | BGSBR | TGSB |  | |
| `CCINS` | DPAYH | MANDT | TB033 |  | |
| `CCINS` | DPAYH | CCINS | TB033 |  | |
| `DTAWS` | DPAYH | MANDT | TFK015W |  | |
| `DTAWS` | DPAYH | ZLAND | TFK015W |  | |
| `DTAWS` | DPAYH | RZAWE | TFK015W |  | |
| `DTAWS` | DPAYH | DTAWS | TFK015W |  | |
| `HBKID` | DPAYH | HBKID | T012 |  | |
| `HBKID` | SYST | MANDT | T012 |  | |
| `HBKID` | T001 | BUKRS | T012 |  | |
| `HKTID` | SYST | MANDT | T012K |  | |
| `HKTID` | T001 | BUKRS | T012K |  | |
| `HKTID` | DPAYH | HBKID | T012K |  | |
| `HKTID` | DPAYH | HKTID | T012K |  | |
| `MANDT` | DPAYH | MANDT | T000 |  | |
| `RZAWE` | T001 | LAND1 | TFK042Z |  | |
| `RZAWE` | DPAYH | RZAWE | TFK042Z |  | |
| `RZAWE` | SYST | MANDT | TFK042Z |  | |
| `UBHKT` | DPAYH | UBHKT | SKA1 |  | |
| `UBHKT` | SYST | MANDT | SKA1 |  | |
| `UBHKT` | T001 | KTOPL | SKA1 |  | |
| `UBNKS` | SYST | MANDT | T005 |  | |
| `UBNKS` | DPAYH | UBNKS | T005 |  | |
| `UZAWE` | SYST | MANDT | T042F |  | |
| `UZAWE` | DPAYH | UZAWE | T042F |  | |
| `WAERS` | DPAYH | WAERS | TCURC |  | |
| `WAERS` | SYST | MANDT | TCURC |  | |
| `ZADNR` | DPAYH | MANDT | ADRC |  | |
| `ZADNR` | DPAYH | ZADNR | ADRC |  | |
| `ZADNR` | * |  | ADRC |  | |
| `ZADNR` | * |  | ADRC |  | |
| `ZBNKS` | SYST | MANDT | T005 |  | |
| `ZBNKS` | DPAYH | ZBNKS | T005 |  | |
| `ZLAND` | DPAYH | ZLAND | T005 |  | |
| `ZLAND` | SYST | MANDT | T005 |  | |
| `ZREGI` | SYST | MANDT | T005S |  | |
| `ZREGI` | DPAYH | ZLAND | T005S |  | |
| `ZREGI` | DPAYH | ZREGI | T005S |  | |
| `ZSPRA` | DPAYH | ZSPRA | T002 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `acc1r`, `doc1r`, `laufd`, `laufi`, `org1r`, `orign`, `payno`, `rwbtr`, `rzawe`, `zaldt`, `zzlocationid`, `zzmid`, `zztxid`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `laufd`, `rzawe`, `zaldt`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `docs-z_paymedium_eft_30.txt`
- `z_change_payment_cond_for_dd.txt`
- `z_paymedium_direct_debit.txt`
- `z_paymedium_eft_30.txt`
- `z_paymedium_hsbccos_refund.txt`
- `ziscrm0021.txt`
- `ziscs_migration_adjustment_m4.txt`
- `zisdm0104.txt`
- `zisfi0024.txt`
- `zisfi0028.txt`
- `zisfi0032.txt`
- `zisfi0041.txt`
- `zisfi0069.txt`
- `zisfi0093.txt`
- `zisfi0094.txt`
- `zisfi0139.txt`
- `zisfi0224.txt`
- `zisfi0334_f01.txt`
- `zisfi0341.txt`
- `ztest_zisfi0066.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
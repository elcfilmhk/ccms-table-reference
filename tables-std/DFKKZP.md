# `DFKKZP`

**Description:** CA Payment Plan — installment payment plan
**Category:** Standard SAP Table
**References:** 158 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkzp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 71 fields | **Data types:** CHAR(51), CUKY(1), CURR(5), DATS(8), DEC(1), NUMC(2), RAW(1), TIMS(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `SELT1` | SELT1_KK | TFK004 | CHAR | 1 | 0 | 1. Selection Category |
| `SELT2` | SELT2_KK | TFK004 | CHAR | 1 | 0 | 2. Selection Category |
| `SELT3` | SELT3_KK | TFK004 | CHAR | 1 | 0 | 3. Selection Category |
| `SELW1` | SELW1_KK | — | CHAR | 35 | 0 | First Field Value to be Selected |
| `SELW2` | SELW2_KK | — | CHAR | 35 | 0 | Second Field Value to be Selected |
| `SELW3` | SELW3_KK | — | CHAR | 35 | 0 | Third Field Value to be Selected |
| `BETRZ` | BETRZ_KK | — | CURR | 13 | 2 | Payment amount in transaction currency |
| `BETRH` | BETRH_KK | — | CURR | 13 | 2 | Amount In Local Currency With +/- Signs |
| `BETRK` | BETRK_KK | — | CURR | 13 | 2 | Assigned Amount in Transaction Currency |
| `BETRL` | BETRL_KK | — | CURR | 13 | 2 | Clarified Amount In Local Currency |
| `XTKLA` | XTKLA_KK | — | CHAR | 1 | 0 | Partial Clarifications Exist For Payment |
| `TBETR` | TBETR_KK | — | CURR | 13 | 2 | Partial Amount that Refers to the Specified Selection |
| `FIKEY` | FIKEY_KK | DFKKSUMC | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `BVRKO` | BVRKO_KK | SKB1 | CHAR | 10 | 0 | Bank clearing account |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `BLART` | BLART_KK | TFK003 | CHAR | 2 | 0 | Document Type |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `KURSF` | KURSF | — | DEC | 9 | 5 | Exchange rate |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `XEIPH` | XEIPH_KK | — | CHAR | 1 | 0 | Create Line Item in General Ledger |
| `AUGRD` | AUGRD_KK | TFK001A | CHAR | 2 | 0 | Clearing Reason |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AETIM` | AETIM_KK | — | TIMS | 6 | 0 | Time at Which the Object Was Last Changed |
| `XRUES` | XRUES_KK | — | CHAR | 1 | 0 | Check was or will be sent back |
| `XAKON` | XAKON_KK | — | CHAR | 1 | 0 | Post Payment on Account |
| `XKLAE` | XKLAE_KK | — | CHAR | 1 | 0 | Clarify Payment Transaction |
| `KLAEB` | KLAEB_KK | — | CHAR | 12 | 0 | Number of Clarification Document |
| `KLAEH` | KLAEH_KK | SKB1 | CHAR | 10 | 0 | Clarification Account |
| `KLAED` | KLAED_KK | — | DATS | 8 | 0 | Posting date of clarif. doc |
| `KLAEC` | KLAEC_KK | — | CHAR | 4 | 0 | Clarification Company Code |
| `OPBEL` | OPBEL_KK | — | CHAR | 12 | 0 | Number of Contract Accts Rec. &amp; Payable Doc. |
| `UPOSZ` | UPOSZ_KK | — | NUMC | 6 | 0 | Allocation key for payment item |
| `UPOSV` | UPOSZ_KK | — | NUMC | 6 | 0 | Allocation key for payment item |
| `TXTVW` | TXTVW_KK | — | CHAR | 80 | 0 | Note to Payee in Payment |
| `CHCKN` | CHCKN_KK | — | CHAR | 13 | 0 | Check number |
| `BANKS` | BANKS | T005 | CHAR | 3 | 0 | Bank country key |
| `BANKL` | BANKL_KK | — | CHAR | 15 | 0 | Bank Number of Other Bank Key |
| `BANKN` | BANKN | — | CHAR | 18 | 0 | Bank account number |
| `BKONT` | BKONT | — | CHAR | 2 | 0 | Bank Control Key |
| `KOINH` | KOINH_KK | — | CHAR | 60 | 0 | Name of Holder of Bank Account/Check Issuer/Cardholder |
| `XPGRO` | XPGRO | — | CHAR | 1 | 0 | Post Office Bank Current Account |
| `XDAUB` | XDAUB_KK | — | CHAR | 1 | 0 | Payment by Standing Order |
| `NRZAA` | NRZAA_KK | — | CHAR | 10 | 0 | Repayment request |
| `REPYM` | REPYM_KK | TFK042Z | CHAR | 1 | 0 | Payment Method for Repayment |
| `XCLAR` | XCLAR_KK | — | CHAR | 1 | 0 | Line item included in clarification worklist |
| `INFOF` | INFOF_KK | — | CHAR | 50 | 0 | Additional information |
| `KUKON` | KUKON_KK | TFK020K | CHAR | 4 | 0 | Short Account Assignment for Transfer Postings |
| `CCINS` | CCINS_KK | TB033 | CHAR | 4 | 0 | Payment card type |
| `CCNUM` | CCNUM | — | CHAR | 25 | 0 | Payment cards: Card number |
| `MERCH` | MERCH | TCCM | CHAR | 15 | 0 | Payment cards: Merchant ID at the clearing house |
| `RUEBL` | RUEBL_KK | — | CHAR | 12 | 0 | Number of the resetting document |
| `RUEAR` | RUEAR_KK | — | CHAR | 1 | 0 | Type of resetting document |
| `BKREF` | BKREF | — | CHAR | 20 | 0 | Reference specifications for bank details |
| `TXTRZ` | TXTRZ_KK | — | CHAR | 50 | 0 | Text For Payment on Account, Repayment, or Transfer Posting |
| `HZUON` | HZUON_KK | — | CHAR | 18 | 0 | Assignment Number in G/L Document |
| `DATAB` | CC_DATAB | — | DATS | 8 | 0 | Payment cards: Valid from |
| `DATBI` | CC_DATBI | — | DATS | 8 | 0 | Payment Cards: Valid To |
| `AUNUM` | AUNUM_KK | — | CHAR | 25 | 0 | Payment cards: Authorization number |
| `AUDAT` | AUDAT_CC | — | DATS | 8 | 0 | Payment cards: Authorization date |
| `AUTIM` | AUTIM | — | TIMS | 6 | 0 | Payment cards: Authorization time |
| `XATTS` | XATTS_KK | — | CHAR | 1 | 0 | Move Attachments of UPOSZ from PSOZA |
| `CGUID` | CARD_GUID | — | RAW | 16 | 0 | GUID of a Payment Card |
| `ENCTP` | CCSECA_ENCTYPE | — | CHAR | 1 | 0 | Type of Encryption |
| `BEGRU` | BEGRU_PL_KK | — | CHAR | 4 | 0 | Authorization Group |
| `IBAN` | IBAN_KK | — | CHAR | 34 | 0 | IBAN (International Bank Account Number) |
| `SWIFT` | BICSW_KK | — | CHAR | 11 | 0 | SWIFT Code/Bank Identifier Code (BIC) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUGRD` | DFKKZP | AUGRD | TFK001A |  | |
| `BANKS` | DFKKZP | BANKS | T005 |  | |
| `BANKS` | DFKKZP | MANDT | T005 |  | |
| `BLART` | DFKKZP | MANDT | TFK003 |  | |
| `BLART` | DFKKZK | APPLK | TFK003 |  | |
| `BLART` | DFKKZP | BLART | TFK003 |  | |
| `BUKRS` | DFKKZP | MANDT | T001 |  | |
| `BUKRS` | DFKKZP | BUKRS | T001 |  | |
| `BVRKO` | DFKKZP | MANDT | SKB1 |  | |
| `BVRKO` | DFKKZP | BUKRS | SKB1 |  | |
| `BVRKO` | DFKKZP | BVRKO | SKB1 |  | |
| `CCINS` | DFKKZP | MANDT | TB033 |  | |
| `CCINS` | DFKKZP | CCINS | TB033 |  | |
| `FIKEY` | DFKKZP | MANDT | DFKKSUMC |  | |
| `FIKEY` | DFKKZP | FIKEY | DFKKSUMC |  | |
| `GSBER` | DFKKZP | MANDT | TGSB |  | |
| `GSBER` | DFKKZP | GSBER | TGSB |  | |
| `KLAEH` | DFKKZP | BUKRS | SKB1 |  | |
| `KLAEH` | DFKKZP | KLAEH | SKB1 |  | |
| `KLAEH` | DFKKZP | MANDT | SKB1 |  | |
| `KUKON` | DFKKZP | KUKON | TFK020K |  | |
| `KUKON` | DFKKZP | MANDT | TFK020K |  | |
| `MERCH` | DFKKZP | MANDT | TCCM |  | |
| `MERCH` | DFKKZP | MERCH | TCCM |  | |
| `REPYM` | DFKKZP | MANDT | TFK042Z |  | |
| `REPYM` | T001 | LAND1 | TFK042Z |  | |
| `REPYM` | DFKKZP | REPYM | TFK042Z |  | |
| `SELT1` | DFKKZP | MANDT | TFK004 |  | |
| `SELT1` | DFKKZK | APPLK | TFK004 |  | |
| `SELT1` | DFKKZP | SELT1 | TFK004 |  | |
| `SELT2` | DFKKZP | SELT2 | TFK004 |  | |
| `SELT2` | DFKKZP | MANDT | TFK004 |  | |
| `SELT2` | DFKKZK | APPLK | TFK004 |  | |
| `SELT3` | DFKKZP | MANDT | TFK004 |  | |
| `SELT3` | DFKKZK | APPLK | TFK004 |  | |
| `SELT3` | DFKKZP | SELT3 | TFK004 |  | |
| `WAERS` | DFKKZP | MANDT | TCURC |  | |
| `WAERS` | DFKKZP | WAERS | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BETRZ`, `KEYZ1`, `KLAEB`, `POSZA`, `WAERS`, `betrz`, `bldat`, `budat`, `fikey`, `infof`, `keyz1`, `opbel`, `ruear`, `selw2`, `xklae`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `bldat`, `budat`, `selw2`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0127.txt`
- `ziscrm0021.txt`
- `ziscs_migration_payment_mock3.txt`
- `zisdm0104.txt`
- `zisfi0003.txt`
- `zisfi0012.txt`
- `zisfi0015.txt`
- `zisfi0023.txt`
- `zisfi0032.txt`
- `zisfi0041.txt`
- `zisfi0093.txt`
- `zisfi0139.txt`
- `zisfi0163.txt`
- `zisfi0224.txt`
- `zisfi0252.txt`
- `zisfi0311.txt`
- `zisfi0318_lcl.txt`
- `zisfi0323_f01.txt`
- `zisfi0323_top.txt`
- `zisfi_bapi_confirm_mobile_pmt.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
# `DFKKRK`

**Description:** Payment Lot Key — lot assignment for payments
**Category:** Standard SAP Table
**References:** 405 SELECT statements across 9 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkrk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 51 fields | **Data types:** CHAR(35), CUKY(2), CURR(4), DATS(5), DEC(1), NUMC(2), TIMS(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KEYR2` | KEYR2_KK | — | CHAR | 40 | 0 | Search term for returns lot |
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `HERKF` | HERKF_KK | TFK001 | CHAR | 2 | 0 | Document Origin Key |
| `FIKEY` | FIKEY_KK | — | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `RLSKO` | RLSKO_KK | TFK012 | CHAR | 10 | 0 | Bank clearing account for returns |
| `GEAKO` | GEAKO_KK | — | CHAR | 10 | 0 | Charges expense account |
| `GEEKO` | GEEKO_KK | — | CHAR | 10 | 0 | Charges revenue account |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `PRCTR` | PRCTR_RL_KK | — | CHAR | 10 | 0 | Profit Center |
| `BLART` | BLART_KK | TFK003 | CHAR | 2 | 0 | Document Type |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `KURSF` | KURSF | — | DEC | 9 | 5 | Exchange rate |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `XEIPH` | XEIPH_KK | — | CHAR | 1 | 0 | Create Line Item in General Ledger |
| `AUGRD` | AUGRD_KK | TFK001A | CHAR | 2 | 0 | Clearing Reason |
| `SELT1` | SELTV_KK | TFK004 | CHAR | 1 | 0 | Default Value for Selection Category |
| `ANZPO` | ANZPO_KK | — | NUMC | 6 | 0 | Number of items |
| `SUMMS` | SUMMS | — | CURR | 15 | 2 | Total debit postings |
| `SUMMH` | SUMMH | — | CURR | 15 | 2 | Total credit postings |
| `SUMWA` | SUMWA_KK | TCURC | CUKY | 5 | 0 | Currency Key for the Totals |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERTIM` | ERTIM_KK | — | TIMS | 6 | 0 | Time at which the object was created |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AETIM` | AETIM_KK | — | TIMS | 6 | 0 | Time at Which the Object Was Last Changed |
| `STARS` | STARS_KK | — | CHAR | 1 | 0 | Status of the returns lot |
| `XSTEB` | XSTEB_KK | — | CHAR | 1 | 0 | Bank Charges Include Tax |
| `XRLSB` | XRLSB_KK | — | CHAR | 1 | 0 | Returns Amounts Include Bank Charges |
| `SKZB1` | SKZB1_KK | T007A | CHAR | 2 | 0 | Tax Code: Bank Charge 1 |
| `SKZB2` | SKZB2_KK | T007A | CHAR | 2 | 0 | Tax Code from Bank 2 |
| `SKZV1` | SKZV1_KK | T007A | CHAR | 2 | 0 | Tax Code: Returns Charge 1 |
| `SKZV2` | SKZV2_KK | T007A | CHAR | 2 | 0 | Tax Code for Return Fees 2 |
| `BANKL` | BANKS | T005 | CHAR | 3 | 0 | Bank country key |
| `BANKK` | BANKK | BNKA | CHAR | 15 | 0 | Bank Keys |
| `BANKN` | BANKN | — | CHAR | 18 | 0 | Bank account number |
| `HBKID` | HBKID | T012 | CHAR | 5 | 0 | Short Key for a House Bank |
| `HKTID` | HKTID | T012K | CHAR | 5 | 0 | ID for account details |
| `JOBNAME` | BTCJOB | — | CHAR | 32 | 0 | Background job name |
| `XCALCGEB` | XRLSCALCGEB_KK | — | CHAR | 1 | 0 | Calculate Charges Automatically |
| `XACCEPTCHARGES` | XACCEPTCHARGES_KK | — | CHAR | 1 | 0 | Returns: Accepting Charges over Tolerance Limit |
| `FLAGS` | FLAGPOOL32 | — | CHAR | 32 | 0 | Status marker |
| `RLMOD` | RLMOD_KK | — | CHAR | 1 | 0 | Returns Posting Type |
| `KSUMS` | KTSUS_KK | — | CURR | 15 | 2 | Specified Debit Total |
| `KSUMH` | KTSUH_KK | — | CURR | 15 | 2 | Specified Credit Total |
| `KSUMP` | KSUMP_KK | — | NUMC | 6 | 0 | Specified Number of Items |
| `XERWR` | XERWR_KK | — | CHAR | 1 | 0 | Enhanced Returns Processing |
| `RLGRD` | RLGRD_KK | — | CHAR | 3 | 0 | Return reason |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUGRD` | DFKKRK | AUGRD | TFK001A |  | |
| `BANKK` | DFKKRK | MANDT | BNKA |  | |
| `BANKK` | DFKKRK | BANKL | BNKA |  | |
| `BANKK` | DFKKRK | BANKK | BNKA |  | |
| `BANKL` | DFKKRK | BANKL | T005 |  | |
| `BANKL` | DFKKRK | MANDT | T005 |  | |
| `BLART` | DFKKRK | MANDT | TFK003 |  | |
| `BLART` | DFKKRK | APPLK | TFK003 |  | |
| `BLART` | DFKKRK | BLART | TFK003 |  | |
| `BUKRS` | DFKKRK | MANDT | T001 |  | |
| `BUKRS` | DFKKRK | BUKRS | T001 |  | |
| `GSBER` | DFKKRK | MANDT | TGSB |  | |
| `GSBER` | DFKKRK | GSBER | TGSB |  | |
| `HBKID` | DFKKRK | MANDT | T012 |  | |
| `HBKID` | DFKKRK | BUKRS | T012 |  | |
| `HBKID` | DFKKRK | HBKID | T012 |  | |
| `HERKF` | DFKKRK | HERKF | TFK001 |  | |
| `HKTID` | DFKKRK | MANDT | T012K |  | |
| `HKTID` | DFKKRK | BUKRS | T012K |  | |
| `HKTID` | DFKKRK | HBKID | T012K |  | |
| `HKTID` | DFKKRK | HKTID | T012K |  | |
| `RLSKO` | DFKKRK | MANDT | TFK012 |  | |
| `RLSKO` | DFKKRK | BUKRS | TFK012 |  | |
| `RLSKO` | DFKKRK | RLSKO | TFK012 |  | |
| `SELT1` | DFKKRK | MANDT | TFK004 |  | |
| `SELT1` | DFKKRK | APPLK | TFK004 |  | |
| `SELT1` | DFKKRK | SELT1 | TFK004 |  | |
| `SKZB1` | DFKKRK | MANDT | T007A |  | |
| `SKZB1` | T005 | KALSM | T007A |  | |
| `SKZB1` | DFKKRK | SKZB1 | T007A |  | |
| `SKZB2` | T005 | KALSM | T007A |  | |
| `SKZB2` | DFKKRK | SKZB2 | T007A |  | |
| `SKZB2` | DFKKRK | MANDT | T007A |  | |
| `SKZV1` | DFKKRK | MANDT | T007A |  | |
| `SKZV1` | T005 | KALSM | T007A |  | |
| `SKZV1` | DFKKRK | SKZV1 | T007A |  | |
| `SKZV2` | DFKKRK | MANDT | T007A |  | |
| `SKZV2` | T005 | KALSM | T007A |  | |
| `SKZV2` | DFKKRK | SKZV2 | T007A |  | |
| `SUMWA` | DFKKRK | SUMWA | TCURC |  | |
| `SUMWA` | DFKKRK | MANDT | TCURC |  | |
| `WAERS` | DFKKRK | MANDT | TCURC |  | |
| `WAERS` | DFKKRK | WAERS | TCURC |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_zcazzintf.txt`
- `z_zcazzintf_rb.txt`
- `zcazzintf.txt`
- `zcazzintf_331.txt`
- `zcazzintf_new.txt`
- `zisfi0127.txt`
- `ztest1_zcazzintf.txt`
- `ztest2_zcazzintf.txt`
- `ztest_zcazzintf.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
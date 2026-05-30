# `DFKKZK`

**Description:** Payment Lot — batch payment lot
**Category:** Standard SAP Table
**References:** 846 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkzk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 51 fields | **Data types:** CHAR(33), CUKY(2), CURR(4), DATS(5), DEC(1), NUMC(4), TIMS(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KEYZ2` | KEYZ2_KK | — | CHAR | 40 | 0 | Search term for payment lot |
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `HERKF` | HERKF_KK | TFK001 | CHAR | 2 | 0 | Document Origin Key |
| `FIKEY` | FIKEY_KK | DFKKSUMC | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `BVRKO` | BVRKO_KK | TFK012 | CHAR | 10 | 0 | Bank clearing account |
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
| `SELT1` | SELTV_KK | TFK004 | CHAR | 1 | 0 | Default Value for Selection Category |
| `SELT2` | SELTV_KK | TFK004 | CHAR | 1 | 0 | Default Value for Selection Category |
| `SELT3` | SELTV_KK | TFK004 | CHAR | 1 | 0 | Default Value for Selection Category |
| `ANZPO` | ANZPO_KK | — | NUMC | 6 | 0 | Number of items |
| `SUMMS` | SUMMS | — | CURR | 15 | 2 | Total debit postings |
| `SUMMH` | SUMMH | — | CURR | 15 | 2 | Total credit postings |
| `SUMWA` | SUMWA_KK | — | CUKY | 5 | 0 | Currency Key for the Totals |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERTIM` | ERTIM_KK | — | TIMS | 6 | 0 | Time at which the object was created |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AETIM` | AETIM_KK | — | TIMS | 6 | 0 | Time at Which the Object Was Last Changed |
| `MAXUP` | MAXUP_KK | — | NUMC | 6 | 0 | Highest Sub-Item Number Assigned |
| `MAXUV` | MAXUP_KK | — | NUMC | 6 | 0 | Highest Sub-Item Number Assigned |
| `STAZS` | STAZS_KK | — | CHAR | 1 | 0 | Status of the payment lot |
| `XSCHS` | XSCHS_KK | — | CHAR | 1 | 0 | Check Lot |
| `XCRDS` | XCRDS_KK | — | CHAR | 1 | 0 | Payment card lot |
| `XZAUS` | XZAUS_KK | — | CHAR | 1 | 0 | Lot for Payment Orders |
| `CCZAH` | CCZAH_KK | — | CHAR | 1 | 0 | Processing Card Payment |
| `SUBEL` | SUBEL_KK | DFKKKO | CHAR | 12 | 0 | Document number of totals posting for check deposit |
| `VKOCH` | VKOCH_KK | — | CHAR | 10 | 0 | Clearing Account for Posting Check Deposits |
| `XEBOK` | XEBOK_KK | — | CHAR | 1 | 0 | Single Posting of Payment Already Completed |
| `XPOSA` | XPOSA_KK | — | CHAR | 1 | 0 | Items Must Not Be Entered Manually |
| `INFOF` | INFOF_KK | — | CHAR | 50 | 0 | Additional information |
| `KTSUS` | KTSUS_KK | — | CURR | 15 | 2 | Specified Debit Total |
| `KTSUH` | KTSUH_KK | — | CURR | 15 | 2 | Specified Credit Total |
| `KSUMP` | KSUMP_KK | — | NUMC | 6 | 0 | Specified Number of Items |
| `XNSEB` | XNSEB_KK | — | CHAR | 1 | 0 | Do Not Create Posting for Check Deposit |
| `JOBNAME` | BTCJOB | — | CHAR | 32 | 0 | Background job name |
| `CHDSK` | CHDSK_KK | — | CHAR | 2 | 0 | Cash Desk |
| `PAYTP` | PAYTP_KK | — | CHAR | 2 | 0 | Category of Payment/Payment Lot |
| `XAUTS` | XAUTS_KK | — | CHAR | 1 | 0 | Automatically Created Lot |
| `CVSCD` | CVSCD_KK | TFKCVS_CODE | CHAR | 3 | 0 | Code for External Payment Collector and Message Category |
| `XEXPY` | XEXTC_KK | — | CHAR | 1 | 0 | Branch Category: Offline or Agent |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUGRD` | DFKKZK | AUGRD | TFK001A |  | |
| `BLART` | DFKKZK | APPLK | TFK003 |  | |
| `BLART` | DFKKZK | BLART | TFK003 |  | |
| `BLART` | DFKKZK | MANDT | TFK003 |  | |
| `BUKRS` | DFKKZK | MANDT | T001 |  | |
| `BUKRS` | DFKKZK | BUKRS | T001 |  | |
| `BVRKO` | DFKKZK | MANDT | TFK012 |  | |
| `BVRKO` | DFKKZK | BUKRS | TFK012 |  | |
| `BVRKO` | DFKKZK | BVRKO | TFK012 |  | |
| `CVSCD` | DFKKZK | MANDT | TFKCVS_CODE |  | |
| `CVSCD` | DFKKZK | CVSCD | TFKCVS_CODE |  | |
| `FIKEY` | DFKKZK | MANDT | DFKKSUMC |  | |
| `FIKEY` | DFKKZK | FIKEY | DFKKSUMC |  | |
| `GSBER` | DFKKZK | MANDT | TGSB |  | |
| `GSBER` | DFKKZK | GSBER | TGSB |  | |
| `HERKF` | DFKKZK | HERKF | TFK001 |  | |
| `SELT1` | DFKKZK | MANDT | TFK004 |  | |
| `SELT1` | DFKKZK | APPLK | TFK004 |  | |
| `SELT1` | DFKKZK | SELT1 | TFK004 |  | |
| `SELT2` | DFKKZK | MANDT | TFK004 |  | |
| `SELT2` | DFKKZK | APPLK | TFK004 |  | |
| `SELT2` | DFKKZK | SELT2 | TFK004 |  | |
| `SELT3` | DFKKZK | MANDT | TFK004 |  | |
| `SELT3` | DFKKZK | APPLK | TFK004 |  | |
| `SELT3` | DFKKZK | SELT3 | TFK004 |  | |
| `SUBEL` | DFKKZK | MANDT | DFKKKO |  | |
| `SUBEL` | DFKKZK | SUBEL | DFKKKO |  | |
| `WAERS` | DFKKZK | MANDT | TCURC |  | |
| `WAERS` | DFKKZK | WAERS | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ERDAT`, `ERTIM`, `FIKEY`, `KEYZ1`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `KEYZ1`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_create_cd_payment_lot.txt`
- `z_bapi_paymentlot.txt`
- `z_zcazzintf.txt`
- `zcazzintf.txt`
- `zcazzintf_331.txt`
- `zcazzintf_new.txt`
- `zfiarc000.txt`
- `zisbw0016.txt`
- `zisfi0012.txt`
- `zisfi0013.txt`
- `zisfi0015.txt`
- `zisfi0041.txt`
- `zisfi0163.txt`
- `zisfi0318_lcl.txt`
- `zisfi0323_f01.txt`
- `zisfi_bapi_confirm_mobile_pmt.txt`
- `zmmpri000.txt`
- `ztest1_zcazzintf.txt`
- `ztest2_zcazzintf.txt`
- `ztest_zcazzintf.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
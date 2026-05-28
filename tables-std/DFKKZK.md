# `DFKKZK`

**Description:** Payment Lot — batch payment lot
**Category:** Standard SAP Table
**References:** 846 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `KEYZ1` | | 🔑 | Primary key |

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

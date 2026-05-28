# `DPAYH`

**Description:** Direct Debit Header — DD payment batch header
**Category:** Standard SAP Table
**References:** 87 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `LAUFD` | | 🔑 | Primary key |
| `LAUFZ` | | 🔑 | Primary key |
| `SEQNO` | | 🔑 | Primary key |

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

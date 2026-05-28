# `DFKKLOCKS`

**Description:** Lock Object — lock/unlock status for CA
**Category:** Standard SAP Table
**References:** 154 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `LOOBJ1` | | 🔑 | Primary key |
| `LOTYP` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `FDATE`, `GPART`, `LOCKR`, `LOOBJ1`, `LOTYP`, `PROID`, `TDATE`, `VKONT`, `lockr`, `loobj1`, `lotyp`, `proid`, `tdate`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `GPART`, `LOOBJ1`, `LOTYP`, `loobj1`, `tdate`

## Join Paths
- `DFKKLOCKS.LOOBJ1` → `DFKKZK.KEYZ1` — Lock → Lot

## Programs Using This Table
- `z_bapi_get_billpay.txt`
- `z_bapi_get_mo_status.txt`
- `z_change_payment_cond_for_dd.txt`
- `z_fkk_db_lock_update1.txt`
- `zis_security_deposit.txt`
- `zisbi0042.txt`
- `zisbi0046.txt`
- `zisbi0133.txt`
- `zisfi0039.txt`
- `zisfi0104.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0142.txt`
- `zisfi0143.txt`
- `zisfi0172.txt`
- `zisfi0173.txt`
- `zisfi0183.txt`
- `zisfi0218.txt`
- `zisfi0300.txt`
- `ztest_mzcs380f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_

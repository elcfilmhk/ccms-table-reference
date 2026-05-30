# `DFKKLOCKS`

**Description:** Lock Object — lock/unlock status for CA
**Category:** Standard SAP Table
**References:** 154 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkklocks/) — validated 2026-05-30, schema v1.0
**Schema fields:** 8 fields | **Data types:** CHAR(5), DATS(2), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `COND_LOOBJ` | LOOBJ_KK | — | CHAR | 32 | 0 | Lock object |
| `ACTKEY` | ACTKEY_KK | TFK080E | CHAR | 2 | 0 | Activity key for conditional business locks |
| `UNAME` | SYUNAME | — | CHAR | 12 | 0 | User Name |
| `ADATUM` | UDATUM | — | DATS | 8 | 0 | Date of Last Change |
| `AZEIT` | UZEIT | — | TIMS | 6 | 0 | Time |
| `PROTECTED` | PROTECTED_KK | — | CHAR | 1 | 0 | Processing lock write-protected |
| `LAUFD` | LAUFD_KK | — | DATS | 8 | 0 | Date ID |
| `LAUFI` | LAUFI_KK | — | CHAR | 6 | 0 | Additional Identification Characteristic |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ACTKEY` | DFKKLOCKS | ACTKEY | TFK080E |  | |
| `LOTYP` | DFKKLOCKS | LOTYP | TFK080B |  | |
| `PROID` | DFKKLOCKS | LOTYP | TFK080C |  | |
| `PROID` | DFKKLOCKS | PROID | TFK080C |  | |

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
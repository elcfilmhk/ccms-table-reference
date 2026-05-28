# `FKKVKP`

**Description:** Contract Account Header — FI-CA contract account master
**Category:** Standard SAP Table
**References:** 1503 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADRNB`, `EZAWE`, `GPART`, `KTOKL`, `SENDCONTROL_GP`, `VKONT`, `ZAHLKOND`, `ZZPREM_FUNC`, `ZZTRADE_CAT`, `ZZTRADE_CLASS`, `abwrh`, `abwvk`, `ebvty`, `erdat`, `ezawe`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ADRNB`, `VKONT`, `abwvk`, `ebvty`, `erdat`, `ezawe`, `gpart`, `ktokl`, `loevm`, `vkont`, `zahlkond`, `zzacctmngr`

## Join Paths
- `FKKVKP.GPART` → `BUT000.PARTNER` — CA → Business Partner
- `FKKVKP.VKONT` → `DFKKOP.VKONTO` — CA → Open Items
- `FKKVKP.VKONT` → `FKKVK.VKONT` — CA Header
- `FKKVKP.VKONT` → `FKK_SEC.VKONT` — CA → Security

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_duedate.txt`
- `z_bapi_mcrs_real_time_refund.txt`
- `z_iscs_get_ca_by_bp.txt`
- `z_isu_sample_z705.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0110.txt`
- `zisbi0142.txt`
- `zisbi0189.txt`
- `ziscs0807.txt`
- `ziscs_pc_customer_det.txt`
- `ziscsami_get_contact_info.txt`
- `ziscseec_get_eher_settings.txt`
- `zisdm0369_ssr_f01_mod.txt`
- `zisfi0039.txt`
- `zisfi0116_test3.txt`
- `zisfi0207.txt`
- `zisfi0219.txt`
- `zisfi0336.txt`
- `zrcs_remove_cons_af.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_

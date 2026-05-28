# Standard SAP Tables in CCMS

> **Note:** These tables do NOT have dictionary HTML files in the CCMS repo. This doc is built from SELECT statement analysis across 17,169 ABAP source files.

**Stats:** 116 standard SAP tables, 14894 total SELECT references across CCMS codebase

## Entity Relationship Overview

```
Business Partner (BP)
  BUT000 ────────── BUT020 (address)
                   └── ADRC (address master)
                   └── ADRP (person)
                   └── ADR6 (email)
                   └── ADR2 (phone)
                   └── BUT050 (role)
                   └── BUT0BK (bank details)
                   └── BUT0ID (ID docs)

Contract Account (CA)
  FKKVKP ─────────── EVER (contract)
  │                  ├── EANL (installation)
  │                  │   ├── EANLH (installation history)
  │                  │   ├── EASTL (rate schedule)
  │                  │   ├── EASTS (schedule)
  │                  │   └── EVBS (premise)
  │                  │       └── EHAUISU (connection object)
  │                  │
  │                  ├── EABL (register)
  │                  │   ├── EABLG (register history)
  │                  │   └── ETDZ (technical register)
  │                  │
  │                  └── EQUI (equipment)
  │                      └── EGPL (device)
  │
  ├── DFKKOP (open items) ─ DFKKKO (doc header)
  ├── FKK_SEC (security deposit)
  ├── FKKVK (CA master)
  └── DFKKLOCKS (locks)

Billing
  ERCH (bill doc) ─── ERCHC (bill line)
  ERDK (FI-CA doc) ─── DFKKKO (doc header)

Sales
  VBAK ───────────── VBAP (item)
  │                  ├── VBKD (conditions)
  │                  └── VBPA (partner)
  │
  └── VBRK (billing) ─ VBRP (bill item)

Change Documents
  CDHDR/CDPOS ─────── EVER (via objectid)

Work Orders
  AUFK ───────────── AFIH (maintenance order)
  │                  └── EITR (tech location)
  │
  VIAUFKST ───────── JEST (status)
```

## Table Details

### `EVER`
**Description:** Contract (IS-U) — master contract between customer and utility
**References:** 1628 SELECT statements | *20* programs
**Key Fields:** `VKONTO`, `VERTRAG`, `ANLAGE`, `MANDT`

**Join Paths:**
- `EVER.VKONTO` → `FKKVKP.VKONT` — Contract → CA
- `EVER.ANLAGE` → `EANL.ANLAGE` — Contract → Installation

**Programs Using This Table:**
- `z_bapi_get_bp_id.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `zisbi0119.txt`
- `zisbi0219f01.txt`
- `ziscs0083.txt`
- `ziscs0151.txt`
- `ziscs0807.txt`
- `zisdm0020.txt`
- _...and 10 more_

---
### `FKKVKP`
**Description:** Contract Account Header — FI-CA contract account master
**References:** 1503 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VKONT`

**Join Paths:**
- `FKKVKP.GPART` → `BUT000.PARTNER` — CA → Business Partner
- `FKKVKP.VKONT` → `DFKKOP.VKONTO` — CA → Open Items
- `FKKVKP.VKONT` → `FKKVK.VKONT` — CA Header
- `FKKVKP.VKONT` → `FKK_SEC.VKONT` — CA → Security

**Programs Using This Table:**
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
- _...and 10 more_

---
### `DFKKOP`
**Description:** CA Open Item — open item line in FI-CA
**References:** 951 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`, `OPUPK`, `OPUPZ`

**Join Paths:**
- `DFKKOP.OPBEL` → `DFKKKO.OPBEL` — Open Item → Doc Header

**Programs Using This Table:**
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zfi_insert_locks_to_openitem.txt`
- `zisbi0201_tp.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisfi0003.txt`
- `zisfi0005_dun.txt`
- `zisfi0069.txt`
- `zisfi0082.txt`
- _...and 10 more_

---
### `DFKKZK`
**Description:** Payment Lot — batch payment lot
**References:** 846 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `KEYZ1`

**Join Paths:**
- Detected in WHERE: `ERDAT, ERTIM, FIKEY, KEYZ1`

**Programs Using This Table:**
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
- _...and 10 more_

---
### `BUT000`
**Description:** Business Partner — BP master (person/org)
**References:** 569 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`

**Join Paths:**
- `BUT000.PARTNER` → `BUT020.PARTNER` — BP → BP Address
- `BUT000.PARTNER` → `BUT050.PARTNER` — BP → BP Role

**Programs Using This Table:**
- `z_bapi_get_bp_id.txt`
- `z_convert_adrc_langu_field.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0053.txt`
- `zisbi0055.txt`
- `zisbi0142.txt`
- `zisbi0204.txt`
- `ziscrm_upd_zcrbpowner.txt`
- `ziscs0031.txt`
- `ziscs0151.txt`
- _...and 10 more_

---
### `EANLH`
**Description:** Installation History — installation validity periods
**References:** 560 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`

**Join Paths:**
- `EANLH.EQUNR` → `EQUI.EQUNR` — Installation History → Equipment

**Programs Using This Table:**
- `zis_write_bwami_extractor.txt`
- `zisbi0055.txt`
- `zisbi0106.txt`
- `ziscs0031.txt`
- `ziscs0086b.txt`
- `ziscs0151.txt`
- `ziscs0169_old.txt`
- `ziscs0170.txt`
- `ziscs0226f_f01.txt`
- `ziscs0243.txt`
- _...and 10 more_

---
### `EABL`
**Description:** Installation Register — meter register at a device location
**References:** 540 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`, `ABLBELNR`

**Join Paths:**
- `EABL.ANLAGE` → `EANL.ANLAGE` — Register → Installation
- `EABL.EQUNR` → `EQUI.EQUNR` — Register → Equipment
- `EABL.ABLBELNR` → `EABLG.ABLBELNR` — Register → Register History

**Programs Using This Table:**
- `z_isdm_create_grpbill_chkread.txt`
- `ziscs0184.txt`
- `ziscs0273.txt`
- `ziscs0525_f01.txt`
- `ziscs_migration_estimate_read.txt`
- `zisdatveri.txt`
- `zisdm0116.txt`
- `zisdm0152.txt`
- `zisdm0159.txt`
- `zisdm0169.txt`
- _...and 10 more_

---
### `EANL`
**Description:** Installation — premise/installation master
**References:** 499 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`

**Join Paths:**
- `EANL.ANLAGE` → `EANLH.ANLAGE` — Installation → History
- `EANL.VSTELLE` → `EVBS.VSTELLE` — Installation → Premise
- `EANL.EQUNR` → `EQUI.EQUNR` — Installation → Equipment

**Programs Using This Table:**
- `z_bapi_get_deposit.txt`
- `z_bapi_get_mr_info_by_premise.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_zsr_popup.txt`
- `z_check_meter_type.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `ziscs0014.txt`
- `ziscs0031.txt`
- _...and 10 more_

---
### `EQUI`
**Description:** Equipment — equipment master
**References:** 425 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `EQUNR`

**Join Paths:**
- `EQUI.EQUNR` → `EGPL.EQUNR` — Equipment → Device

**Programs Using This Table:**
- `z_iscs_update_meter_so.txt`
- `z_isdm_create_grpbill_chkread.txt`
- `z_isdm_lpb_ready_check.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `ziscs0273.txt`
- `zisdatveri.txt`
- `zisdm0091.txt`
- `zisdm0130.txt`
- `zisdm0152.txt`
- `zisdm0169.txt`
- _...and 10 more_

---
### `FKKZEST`
**Description:** Billing Index Summary — billing summary by CA
**References:** 412 SELECT statements | *15* programs
**Key Fields:** `MANDT`, `RUNID`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_zcazzintf.txt`
- `z_zcazzintf_rb.txt`
- `zcazzintf.txt`
- `zcazzintf_331.txt`
- `zcazzintf_new.txt`
- `zfiapc000.txt`
- `zisfi0003.txt`
- `zisfi0280.txt`
- `zisfi0311b_f01.txt`
- `zisfi0318_lcl.txt`
- _...and 5 more_

---
### `DFKKRK`
**Description:** Payment Lot Key — lot assignment for payments
**References:** 405 SELECT statements | *9* programs
**Key Fields:** `MANDT`, `KEYZ1`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
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
### `ERDK`
**Description:** FI-CA Contract Document — financial contract document
**References:** 375 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`

**Join Paths:**
- `ERDK.OPBEL` → `DFKKKO.OPBEL` — FI-CA Doc → Doc Header

**Programs Using This Table:**
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `zisbi0006.txt`
- `zisbi0084.txt`
- `zisbi0086.txt`
- `zisbi0151.txt`
- `zisbi0201_tp.txt`
- `zisbi0219f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- _...and 10 more_

---
### `EASTS`
**Description:** Installation Schedule — scheduled tariff/rate periods
**References:** 339 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`

**Join Paths:**
- Detected in WHERE: `AB, ANLAGE, BIS, LOGIKZW, TARIFART, ZWNABR`

**Programs Using This Table:**
- `z_iscrm_check_ami_end.txt`
- `z_iscrm_check_ami_mo.txt`
- `z_isdm_get_ami_effective_date.txt`
- `z_isdm_lpb_ready_check.txt`
- `zisbi0017.txt`
- `ziscs0031.txt`
- `ziscs0273.txt`
- `zisdm0091.txt`
- `zisdm0116.txt`
- `zisdm0159.txt`
- _...and 10 more_

---
### `EVBS`
**Description:** Premise — premise/installation location
**References:** 317 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VSTELLE`, `HAUS`

**Join Paths:**
- `EVBS.HAUS` → `EHAUISU.HAUS` — Premise → Connection Object

**Programs Using This Table:**
- `z_adms_ccms_call_take.txt`
- `z_adms_ccms_cust_query_1a.txt`
- `z_bapi_get_deposit.txt`
- `z_bapi_simple_accinfo.txt`
- `z_iscs_suppressmovein.txt`
- `z_isdm_get_premise_ext.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0011.txt`
- `ziscs0048.txt`
- `ziscs0068.txt`
- _...and 10 more_

---
### `ERCH`
**Description:** Billing Document (IS-U) — invoice/bill header
**References:** 301 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `BELNR`, `GJAHR`

**Join Paths:**
- `ERCH.BELNR` → `ERCHC.BELNR` — Bill Doc → Bill Doc Line
- `ERCH.OPBEL` → `ERDK.OPBEL` — Bill Doc → FI-CA Doc

**Programs Using This Table:**
- `z_iscrm_check_ami_end.txt`
- `z_select_rfi38_data.txt`
- `zisbi0011.txt`
- `zisbi0057.txt`
- `zisbi0091.txt`
- `zisbi0099.txt`
- `zisbi0110.txt`
- `zisbi0214f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- _...and 10 more_

---
### `ADRC`
**Description:** Address — address master data
**References:** 276 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `ADDRNUMBER`

**Join Paths:**
- Detected in WHERE: `ADDRNUMBER, CITY2, HOUSE_NUM1, NATION, STREET, STR_SUPPL1`

**Programs Using This Table:**
- `z_bapi_get_mo_status.txt`
- `z_get_chin_supply_address_ws.txt`
- `z_get_supply_address_ws.txt`
- `zisbi0011.txt`
- `ziscrm0048.txt`
- `ziscs0031.txt`
- `ziscs0088.txt`
- `ziscs0108.txt`
- `ziscs0150.txt`
- `ziscs0151.txt`
- _...and 10 more_

---
### `ETDZ`
**Description:** Technical Register Data — meter reading register data
**References:** 240 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `EQUNR`

**Join Paths:**
- `ETDZ.EQUNR` → `EQUI.EQUNR` — Tech Register → Equipment

**Programs Using This Table:**
- `z_bi_lp_prof_val.txt`
- `ziscs0149.txt`
- `ziscs0534_f01.txt`
- `ziscs0717_form.txt`
- `zisdm0022f01.txt`
- `zisdm0086.txt`
- `zisdm0091.txt`
- `zisdm0136c.txt`
- `zisdm0136d.txt`
- `zisdm0170.txt`
- _...and 10 more_

---
### `EABLG`
**Description:** Installation Register History — historical register records
**References:** 216 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ABLBELNR`

**Join Paths:**
- Detected in WHERE: `ABLBELNR, ABLESGR, ADATSOLL, ANLAGE, ablbelnr, ableinh`

**Programs Using This Table:**
- `ziscs0023.txt`
- `ziscs0184.txt`
- `ziscs0207.txt`
- `ziscs0273.txt`
- `zisdh0026.txt`
- `zisdm0091.txt`
- `zisdm0136c.txt`
- `zisdm0159.txt`
- `zisdm0170.txt`
- `zisdm0177.txt`
- _...and 10 more_

---
### `FKKVK`
**Description:** Contract Account — CA master record
**References:** 214 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VKONT`

**Join Paths:**
- Detected in WHERE: `ERDAT, VKONT, VKTYP, loevm, vkont, vktyp`

**Programs Using This Table:**
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_gs_info.txt`
- `z_bapi_simple_accinfo.txt`
- `z_bapi_webid_forget.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0006.txt`
- `zisbi0142.txt`
- `ziscrm0006f01.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- _...and 10 more_

---
### `CDPOS`
**Description:** Change Document Position — change log line items
**References:** 196 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OBJCLAS`, `OBJID`, `CHANGENR`, `TABNAME`, `FNAME`

**Join Paths:**
- `CDPOS.OBJECTID` → `EVER.VKONTO` — Change Docs → Contract

**Programs Using This Table:**
- `zbacbe034.txt`
- `zfi_defer_to_by_changeid.txt`
- `zisbi0075.txt`
- `zisbi0091.txt`
- `zisbi0142.txt`
- `zisbw0030.txt`
- `ziscs0093.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- `ziscs0169_old.txt`
- _...and 10 more_

---
### `EASTL`
**Description:** Installation Rate Schedule — rate tariff assignment
**References:** 182 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`, `LOGIKNR`

**Join Paths:**
- Detected in WHERE: `AB, ANLAGE, BIS, LOGIKNR, ab, anlage`

**Programs Using This Table:**
- `method-eligibility_check.txt`
- `z_iscrm_check_ami_end.txt`
- `z_iscrm_check_ami_mo.txt`
- `ziscs0023.txt`
- `ziscs0108.txt`
- `ziscs0184.txt`
- `ziscs0207.txt`
- `ziscs0254.txt`
- `ziscs0273.txt`
- `ziscs0525_f01.txt`
- _...and 10 more_

---
### `DFKKKO`
**Description:** CA Document Header — FI-CA document header
**References:** 174 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`

**Join Paths:**
- Detected in WHERE: `BLART, BUDAT, CPUDT, ERNAM, HERKF, OPBEL`

**Programs Using This Table:**
- `z_isbi_reverseclr_rebill.txt`
- `zisbi0032.txt`
- `zisbi0225f01.txt`
- `ziscs0088.txt`
- `ziscs0517forms.txt`
- `ziscs1118.txt`
- `ziscs_migration_adjustment.txt`
- `ziscs_migration_financial_tran.txt`
- `zisfi0036.txt`
- `zisfi0069.txt`
- _...and 10 more_

---
### `CDHDR`
**Description:** Change Document Header — change log header
**References:** 173 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OBJCLAS`, `OBJID`, `CHANGENR`

**Join Paths:**
- Detected in WHERE: `OBJECTCLAS, UDATE, changenr, objectclas, objectid, username`

**Programs Using This Table:**
- `zbacbe034.txt`
- `zisbi0075.txt`
- `zisbi0091.txt`
- `zisbi0142.txt`
- `zisbw0030.txt`
- `ziscs0093.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- `ziscs0169_old.txt`
- `ziscs0173.txt`
- _...and 10 more_

---
### `DFKKZP`
**Description:** CA Payment Plan — installment payment plan
**References:** 158 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`, `POSZA`

**Join Paths:**
- Detected in WHERE: `BETRZ, KEYZ1, KLAEB, POSZA, WAERS, betrz`

**Programs Using This Table:**
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
- _...and 10 more_

---
### `DFKKLOCKS`
**Description:** Lock Object — lock/unlock status for CA
**References:** 154 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `LOOBJ1`, `LOTYP`

**Join Paths:**
- `DFKKLOCKS.LOOBJ1` → `DFKKZK.KEYZ1` — Lock → Lot

**Programs Using This Table:**
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
- _...and 10 more_

---
### `VIAFKOS`
**Description:** Service Order — service order header
**References:** 153 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- Detected in WHERE: `AUART, AUFNR, IPHAS, KTEXT, adrnr, aedat`

**Programs Using This Table:**
- `z_dunning_create_so.txt`
- `ziscs0031.txt`
- `ziscs0149.txt`
- `ziscs0161.txt`
- `ziscs0182.txt`
- `ziscs0254.txt`
- `ziscs0364.txt`
- `ziscsriaufk20.txt`
- `zisdm0067.txt`
- `zisdm0142.txt`
- _...and 10 more_

---
### `ETTIFN`
**Description:** Installation Billing Index — billing history index
**References:** 145 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `ANLAGE`, `BELNR`

**Join Paths:**
- Detected in WHERE: `AB, ANLAGE, BELNR, BETRAG, BIS, INAKTIV`

**Programs Using This Table:**
- `z_bapi_get_bill_csmpt.txt`
- `z_calculate_deposit.txt`
- `z_isdm_get_ami_effective_date.txt`
- `zeedm_ptr.txt`
- `zisbi0026.txt`
- `zisbi0151.txt`
- `zisbiami_calc_bill_costs.txt`
- `zisbw0021.txt`
- `ziscs0090.txt`
- `ziscs0121.txt`
- _...and 10 more_

---
### `VBAK`
**Description:** Sales Document Header — sales order header
**References:** 137 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`

**Join Paths:**
- `VBAK.VBELN` → `VBAP.VBELN` — Sales Header → Item
- `VBAK.VBELN` → `VBPA.VBELN` — Sales Header → Partner
- `VBAK.VBELN` → `VBKD.VBELN` — Sales Header → Conditions
- `VBAK.VBELN` → `VBRK.VBELN` — Sales → Billing

**Programs Using This Table:**
- `zisfi0121.txt`
- `zisfi0238_bw.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- `zissd00056.txt`
- _...and 10 more_

---
### `FKK_SEC`
**Description:** Security Deposit — CA security deposit
**References:** 109 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VKONT`, `SECID`

**Join Paths:**
- Detected in WHERE: `ACC, NON_CASH, SECURITY, VKONT, aedat, aenam`

**Programs Using This Table:**
- `z_calculate_deposit.txt`
- `z_isu_event_0830.txt`
- `z_sec_rep_rel.txt`
- `zis_security_deposit.txt`
- `zisbi0030.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisdatveri.txt`
- `zisfi0010.txt`
- `zisfi0025_corr_print.txt`
- `zisfi0039.txt`
- _...and 10 more_

---
### `BUT020`
**Description:** BP Address — address assignments for BP
**References:** 106 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`, `ADDRNUMBER`, `NATION`

**Join Paths:**
- `BUT020.ADDRNUMBER` → `ADRC.ADDRNUMBER` — Address Ref → Address
- `BUT020.PERSNUMBER` → `ADRP.PERSNUMBER` — Person → Person Master

**Programs Using This Table:**
- `z_bapi_get_address.txt`
- `z_iscrm_check_pa_validity.txt`
- `zaccount.txt`
- `ziscrm_patch_adrc_lang_bp_type.txt`
- `ziscs0002.txt`
- `ziscs0007.txt`
- `ziscs0019.txt`
- `ziscs0080.txt`
- `ziscs0105.txt`
- `ziscs0132.txt`
- _...and 10 more_

---
### `VBAP`
**Description:** Sales Document Item — sales order item
**References:** 105 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`

**Join Paths:**
- Detected in WHERE: `abgru, arktx, cuobj, erdat, kondm, kwmeng`

**Programs Using This Table:**
- `ziscs0522_f01.txt`
- `ziscseec_comm_frmwrk_eeus_ea.txt`
- `zisfi0121.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- _...and 10 more_

---
### `VBPA`
**Description:** Sales Document Partner — partner addresses
**References:** 99 SELECT statements | *5* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`, `PARVW`

**Join Paths:**
- Detected in WHERE: `kunnr, parvw, vbeln`

**Programs Using This Table:**
- `zissd00100.txt`
- `zissd00101.txt`
- `zsdisn001.txt`
- `zsdsodl02.txt`
- `zsdsopoc1.txt`

---
### `ADR2`
**Description:** Phone Number — phone number assignments
**References:** 97 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `ADDRNUMBER`, `PERSNUMBER`, `CONSNUMBER`

**Join Paths:**
- Detected in WHERE: `addrnumber, consnumber, date_from, persnumber, r3_user`

**Programs Using This Table:**
- `z_bapi_account_mgr_by_ca.txt`
- `z_bapi_bp_details.txt`
- `z_update_crm_bp.txt`
- `zadru_create.txt`
- `ziscs0031.txt`
- `ziscs0238.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0368.txt`
- `ziscs_sms02.txt`
- _...and 10 more_

---
### `DD03L`
**Description:** Table Field — DDIC field definitions
**References:** 95 SELECT statements | *20* programs
**Key Fields:** `TABNAME`, `FIELDNAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_fi_fill_fkkvkp_s_di.txt`
- `zbacbe034.txt`
- `zbacbe106_ssa_cat.txt`
- `zcazzi000.txt`
- `ziscrmact_queue.txt`
- `ziscs0601i02.txt`
- `ziscs_pon_export_ca.txt`
- `ziscs_pon_import_sent_hist.txt`
- `ziscv_datamask_thread.txt`
- `zisdm0098.txt`
- _...and 10 more_

---
### `EPROFASS`
**Description:** Energy Profile Assignment — rate profile assignment
**References:** 91 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `PROFILE`, `LOGIKZW`

**Join Paths:**
- Detected in WHERE: `datefrom, dateto, logikzw, profile, timeto`

**Programs Using This Table:**
- `z_cs_cxt_add_consum.txt`
- `z_isdm_consumption_details.txt`
- `z_isdm_registers_validation.txt`
- `z_write_bwfit_extractor.txt`
- `zisdm0102.txt`
- `zisdm0128f01.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0212.txt`
- `zisdm0213.txt`
- _...and 10 more_

---
### `AUFK`
**Description:** Order Header — maintenance/service order
**References:** 88 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- `AUFK.AUFNR` → `AFIH.AUFNR` — Order → Maintenance Order

**Programs Using This Table:**
- `method-read_serv_ord_stat_info.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_updateso.txt`
- `zdiscon.txt`
- `zggbr000.txt`
- `zisbi0013.txt`
- `zisbi0186.txt`
- `ziscrm0318forms.txt`
- `ziscs0002.txt`
- `ziscs0007.txt`
- _...and 10 more_

---
### `DPAYH`
**Description:** Direct Debit Header — DD payment batch header
**References:** 87 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `LAUFD`, `LAUFZ`, `SEQNO`

**Join Paths:**
- Detected in WHERE: `acc1r, doc1r, laufd, laufi, org1r, orign`

**Programs Using This Table:**
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
- _...and 10 more_

---
### `VBKD`
**Description:** Sales Document Business Data — business conditions
**References:** 85 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`

**Join Paths:**
- Detected in WHERE: `posnr, vbeln, vkont`

**Programs Using This Table:**
- `z_bapi_multi_ecodata_profile.txt`
- `ziscseec_eeus_reb_det.txt`
- `zissd00001.txt`
- `zissd00005.txt`
- `zissd00013.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00024.txt`
- `zissd00042.txt`
- `zissd00047.txt`
- _...and 10 more_

---
### `EHAUISU`
**Description:** Connection Object — premise connection object
**References:** 79 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `HAUS`

**Join Paths:**
- Detected in WHERE: `HAUS, counc, haus, regiogroup, regpolit`

**Programs Using This Table:**
- `z_isdm_mol_map_fc_loc.txt`
- `ziscrm0318forms.txt`
- `ziscs0022.txt`
- `ziscs0146.txt`
- `ziscs0184.txt`
- `ziscs0283.txt`
- `zisdm0022_bulk.txt`
- `zisdm0051.txt`
- `zisdm0058.txt`
- `zisdm0084.txt`
- _...and 10 more_

---
### `JEST`
**Description:** Object Status — system status entries
**References:** 79 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OBJNR`, `STAT`

**Join Paths:**
- Detected in WHERE: `INACT, OBJNR, STAT, inact, objnr, stat`

**Programs Using This Table:**
- `z_bapi_get_ft_status.txt`
- `z_bapi_iia_change_a.txt`
- `z_bapi_iia_dates_getlist_d.txt`
- `z_bapi_srvord_chg.txt`
- `z_isdm_get_meter_reg.txt`
- `z_isu_create_order.txt`
- `zisbi0025.txt`
- `zisbi0025_1.txt`
- `ziscs0002.txt`
- `ziscs0005.txt`
- _...and 10 more_

---
### `ERCHC`
**Description:** Billing Document Line — line items for billing doc
**References:** 74 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`

**Join Paths:**
- Detected in WHERE: `belnr, intbudat, intcpudt, intopbel, opbel`

**Programs Using This Table:**
- `z_bapi_get_billpay_hist_date.txt`
- `z_isbi_get_bill_invoice_docs.txt`
- `zisbi0014.txt`
- `zisbi0014t.txt`
- `zisbi0026.txt`
- `zisbi0042.txt`
- `zisbi0046.txt`
- `zisbi0054.txt`
- `zisbi0057.txt`
- `zisbi0061.txt`
- _...and 10 more_

---
### `BUT0ID`
**Description:** BP Identification — ID documents
**References:** 74 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`, `TYPE`, `IDNUMBER`

**Join Paths:**
- Detected in WHERE: `idnumber, partner, type`

**Programs Using This Table:**
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_bapi_val_iden.txt`
- `z_bp_id_validation.txt`
- `ziscrm0006f01.txt`
- `ziscrm0008f01.txt`
- `ziscrm0010f01.txt`
- `ziscrm0031f01.txt`
- `ziscs0244.txt`
- _...and 10 more_

---
### `BUT0BK`
**Description:** BP Bank Details — bank account info
**References:** 71 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`, `BANKN`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_bapi_bank_details.txt`
- `z_bapi_bank_details_noname.txt`
- `z_bapi_get_ap_status.txt`
- `z_bapi_get_track_mo.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_check_ca_ebill_autopay.txt`
- `z_get_bank_name.txt`
- `z_paymedium_eft_30.txt`
- `ziscs0184.txt`
- `ziscs0802_f01.txt`
- _...and 10 more_

---
### `VIAUFKS`
**Description:** Order (IS-U) — IS-U order master
**References:** 71 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- Detected in WHERE: `AUART, AUFNR, ERDAT, GSTRP, IDAT2, ILART`

**Programs Using This Table:**
- `z_bapi_premise_validation_f.txt`
- `z_bapi_validate_premise.txt`
- `zdiscon.txt`
- `zisbi0173.txt`
- `zisbi0198.txt`
- `zisbw0043.txt`
- `ziscrm0318forms.txt`
- `ziscs0038.txt`
- `ziscs0153.txt`
- `ziscs0273.txt`
- _...and 10 more_

---
### `BUT0CC`
**Description:** BP Credit Card — credit card info
**References:** 68 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`, `BANKCT`

**Join Paths:**
- Detected in WHERE: `CC2`

**Programs Using This Table:**
- `z_bapi_chk_but0bk_but0cc.txt`
- `z_check_ca_ebill_autopay.txt`
- `z_get_bank_name.txt`
- `ziscrm_patch_bp_payment_card.txt`
- `ziscs0322.txt`
- `ziscv03.txt`
- `ziscv06a.txt`
- `ziscv11_f01.txt`
- `ziscv11nv_f01.txt`
- `ziscv13_f01.txt`
- _...and 10 more_

---
### `EAUS`
**Description:** Move-Out Document — end of supply document
**References:** 65 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VERTRAG`, `AUSZBELEG`

**Join Paths:**
- Detected in WHERE: `AUSZBELEG, ERDAT, KUNDE, STORAUSZ, VKONT, aedat`

**Programs Using This Table:**
- `z_bapi_get_track_mo.txt`
- `z_calculate_deposit.txt`
- `z_get_ca_bp_modoc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0161.txt`
- `ziscs0177.txt`
- `ziscs0184.txt`
- `ziscs0289f.txt`
- `ziscs0436.txt`
- `zisfi0027.txt`
- _...and 10 more_

---
### `VIAUFKST`
**Description:** Order Tracking — order status tracking
**References:** 59 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- `VIAUFKST.AUFNR` → `AUFK.AUFNR` — WO Tracking → Order
- `VIAUFKST.OBJNR` → `JEST.OBJNR` — WO Tracking → Status

**Programs Using This Table:**
- `z_bapi_get_cl_status.txt`
- `z_bapi_get_ft_status.txt`
- `z_bapi_get_mi_status.txt`
- `z_bapi_get_track_cl.txt`
- `z_bapi_get_track_mi.txt`
- `zdiscon.txt`
- `zisbi0013.txt`
- `ziscs0026.txt`
- `ziscs0026a.txt`
- `ziscs0039.txt`
- _...and 10 more_

---
### `USR21`
**Description:** User Address Key — user-address mapping
**References:** 50 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `BNAME`

**Join Paths:**
- Detected in WHERE: `ADDRNUMBER, BNAME, MANDT, PERSNUMBER, addrnumber, bname`

**Programs Using This Table:**
- `z_bapi_account_mgr_by_ca.txt`
- `z_ossnote_436119_adrnum_pernum.txt`
- `zbacbe034.txt`
- `zbacotype.txt`
- `zcazze003.txt`
- `ziscrm0010f01.txt`
- `ziscrm0014.txt`
- `ziscrm0031f01.txt`
- `ziscs0031.txt`
- `ziscs0176.txt`
- _...and 10 more_

---
### `ADR6`
**Description:** Email Address — email addresses
**References:** 48 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `ADDRNUMBER`, `PERSNUMBER`, `CONSNUMBER`

**Join Paths:**
- Detected in WHERE: `addrnumber, consnumber, date_from, flgdefault, persnumber`

**Programs Using This Table:**
- `z_bapi_account_mgr_by_ca.txt`
- `z_wy_lfa1_single_read.txt`
- `zisbi0120.txt`
- `ziscrm0014.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0467.txt`
- `ziscs0807_test_radica_f01.txt`
- _...and 10 more_

---
### `EAUSV`
**Description:** Move-Out Document V — end of supply with more fields
**References:** 47 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VERTRAG`, `AUSZBELEG`

**Join Paths:**
- Detected in WHERE: `ANLAGE, AUSZBELEG, AUSZDAT, STORAUSZ, VERTRAG, VSTELLE`

**Programs Using This Table:**
- `z_crm_isu_contracts.txt`
- `z_iscs_contract_chng_doc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0019.txt`
- `ziscs0028.txt`
- `ziscs0038.txt`
- `ziscs0067.txt`
- `ziscs0184.txt`
- `ziscs0252f01.txt`
- `ziscs0436.txt`
- _...and 10 more_

---
### `USR02`
**Description:** User Master — user logon data
**References:** 47 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `BNAME`

**Join Paths:**
- Detected in WHERE: `ANAME, BCDA1, BCODE, BNAME, CLASS, CODVN`

**Programs Using This Table:**
- `z_abap_developer_info.txt`
- `z_zcsh_pid_maint2.txt`
- `zbacbe001.txt`
- `zbacbe004.txt`
- `zbacbe033.txt`
- `zbacbe034.txt`
- `zbacbe036.txt`
- `zbacbe042.txt`
- `zbacbe045.txt`
- `zbacbe060.txt`
- _...and 10 more_

---
### `FKKMAZE`
**Description:** CA Line Item — FI-CA document line items
**References:** 46 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `OPBEL`

**Join Paths:**
- Detected in WHERE: `gpart, laufd, laufi, mahns, opbel, opupk`

**Programs Using This Table:**
- `zisbi0079.txt`
- `zisbi0224forms.txt`
- `ziscs0065.txt`
- `zisdm0282.txt`
- `zisfi0005_dun.txt`
- `zisfi0038.txt`
- `zisfi0040.txt`
- `zisfi0040_perf_tuning.txt`
- `zisfi0042.txt`
- `zisfi0101.txt`
- _...and 10 more_

---
### `AFIH`
**Description:** Maintenance Order Header — PM order header
**References:** 45 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- `AFIH.ILOA` → `EITR.ILOA` — Maint Order → Tech Location

**Programs Using This Table:**
- `method-check_open_order_exists.txt`
- `method-read_pmacttype.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_isusmorder_exch.txt`
- `z_validate_n_transfer_mt.txt`
- `zisbi0104.txt`
- `ziscrm0318forms.txt`
- `ziscs0016.txt`
- `ziscs0027.txt`
- `ziscs0153.txt`
- _...and 10 more_

---
### `DD02L`
**Description:** Table — DDIC table definitions
**References:** 43 SELECT statements | *18* programs
**Key Fields:** `TABNAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbacbe023.txt`
- `zbacbe024.txt`
- `zbacbe034.txt`
- `zbacbe100.txt`
- `zbacbe101.txt`
- `zbacbe106_get_rows_count.txt`
- `zbacbe106_ssa_cat.txt`
- `zbacbe201_f01.txt`
- `zjivs_delim_check.txt`
- `zjivs_dyn_adk.txt`
- _...and 8 more_

---
### `EKPO`
**Description:** Purchasing Document Item — PO item
**References:** 42 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `EBELN`, `EBELP`

**Join Paths:**
- Detected in WHERE: `AEDAT, ANFNR, ANFPS, BANFN, BNFPO, BPRME`

**Programs Using This Table:**
- `z_create_ekrs.txt`
- `zdemo.txt`
- `ziscs0120.txt`
- `zissd00031.txt`
- `zissd00041.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- _...and 10 more_

---
### `FKK_SEC_N`
**Description:** Security Deposit Notice — security notice records
**References:** 34 SELECT statements | *19* programs
**Key Fields:** `MANDT`, `VKONT`, `SECID`

**Join Paths:**
- Detected in WHERE: `NC_STATUS, REFNO, SECURITY, SEC_EXPIRE, TYP, nc_status`

**Programs Using This Table:**
- `z_calculate_deposit.txt`
- `z_get_security_deposit.txt`
- `ziscs0088.txt`
- `zisfi0025.txt`
- `zisfi0036.txt`
- `zisfi0037.txt`
- `zisfi0038.txt`
- `zisfi0045.txt`
- `zisfi0051.txt`
- `zisfi0052.txt`
- _...and 9 more_

---
### `BUT050`
**Description:** BP Role — role assignments for BP
**References:** 33 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `PARTNER`, `RLTYP`

**Join Paths:**
- Detected in WHERE: `PARTNER2, partner1, partner2, reltyp`

**Programs Using This Table:**
- `method-populate_output_file.txt`
- `z_bapi_account_mgr_by_ca.txt`
- `zisbi0075.txt`
- `ziscrm0037.txt`
- `ziscrm0040.txt`
- `ziscs0078.txt`
- `ziscs0084.txt`
- `ziscs0151.txt`
- `ziscs0376.txt`
- `ziscs0467.txt`
- _...and 10 more_

---
### `FKKMAKO`
**Description:** Direct Debit Agreement — payment method setup
**References:** 32 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `LAUFD`, `LAUFI`, `VKONT`

**Join Paths:**
- Detected in WHERE: `ausdt, gpart, laufd, laufi, mazae, vkont`

**Programs Using This Table:**
- `z_bapi_check_dunning_hist.txt`
- `zisbi0097.txt`
- `zisbw0014.txt`
- `ziscs_migration_custcontact_m3.txt`
- `ziscs_migration_custcontact_m4.txt`
- `zisdm0282.txt`
- `zisfi0025.txt`
- `zisfi0040.txt`
- `zisfi0044.txt`
- `zisfi0097.txt`
- _...and 10 more_

---
### `VBRK`
**Description:** Billing Document Header — billing/invoice header
**References:** 32 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`

**Join Paths:**
- Detected in WHERE: `aedat, erdat, fkart, fkdat, fksto, fktyp`

**Programs Using This Table:**
- `zisbi0013.txt`
- `ziscs0040.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00012.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- _...and 10 more_

---
### `EKKO`
**Description:** Purchasing Document Header — PO header
**References:** 32 SELECT statements | *16* programs
**Key Fields:** `MANDT`, `EBELN`

**Join Paths:**
- `EKKO.EBELN` → `EKPO.EBELN` — PO Header → PO Item
- `EKKO.EBELN` → `EKBE.EBELN` — PO → History

**Programs Using This Table:**
- `z_create_ekrs.txt`
- `zbacbe034.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- `zissd00108.txt`
- `zissd_get_oa_validity_price.txt`
- _...and 6 more_

---
### `VBRP`
**Description:** Billing Document Item — billing line item
**References:** 31 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`

**Join Paths:**
- Detected in WHERE: `aubel, aupos, erdat, erzet, matnr, netwr`

**Programs Using This Table:**
- `ziscs0523_f01.txt`
- `zisfi0030.txt`
- `zisfi0235.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- _...and 10 more_

---
### `EPROFHEAD`
**Description:** Energy Profile Header — rate profile master
**References:** 31 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `PROFILE`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `method-get_data.txt`
- `method-vee_manual_edit.txt`
- `z_conv_kvarh_to_kva_fit.txt`
- `z_isdm_get_formula_profile.txt`
- `z_write_bwami_extractor.txt`
- `z_write_bwfit_extractor.txt`
- `zedm_ext_30int_sub_forms.txt`
- `zisdm0022f01.txt`
- `zisdm0205.txt`
- `zisdm0209_evf01.txt`
- _...and 10 more_

---
### `FKK_SEC_C`
**Description:** Security Deposit Cancel — cancelled security
**References:** 30 SELECT statements | *17* programs
**Key Fields:** `MANDT`, `VKONT`, `SECID`

**Join Paths:**
- Detected in WHERE: `REQUEST, SECURITY, VTREF`

**Programs Using This Table:**
- `method-check_ca_deposit.txt`
- `z_calculate_deposit.txt`
- `z_get_security_deposit.txt`
- `ziscs0088.txt`
- `ziscs_sms02.txt`
- `zisfi0025.txt`
- `zisfi0037.txt`
- `zisfi0038.txt`
- `zisfi0045.txt`
- `zisfi0052.txt`
- _...and 7 more_

---
### `CDPOS_STR`
**Description:** SAP standard table
**References:** 30 SELECT statements | *2* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisdm0078f01.txt`
- `zisdm0414f01.txt`

---
### `BKPF`
**Description:** Accounting Document Header — FI doc header
**References:** 29 SELECT statements | *11* programs
**Key Fields:** `MANDT`, `BUKRS`, `BELNR`, `GJAHR`

**Join Paths:**
- `BKPF.BELNR` → `BSEG.BELNR` — FI Header → FI Line Item

**Programs Using This Table:**
- `zbacbe034.txt`
- `zfchzuord_2.txt`
- `zisfi0029.txt`
- `zisfi0043.txt`
- `zisfi0083.txt`
- `zisfi0083_1.txt`
- `zisfi0083_1t.txt`
- `zisfi0083_2.txt`
- `zisfi0090.txt`
- `zisfi0238_bw.txt`
- _...and 1 more_

---
### `T001`
**Description:** Company Code — company code master
**References:** 26 SELECT statements | *17* programs
**Key Fields:** `BUKRS`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_bapi_ml001.txt`
- `zbacbe034.txt`
- `zisbi0018.txt`
- `zisbi0019.txt`
- `zisbi0045.txt`
- `zisdm0080.txt`
- `zisdm0084.txt`
- `zisdm0089.txt`
- `zisfi0046.txt`
- `zisfi0090.txt`
- _...and 7 more_

---
### `AFVU`
**Description:** Order Operation User Fields — operation extensions
**References:** 25 SELECT statements | *13* programs
**Key Fields:** `MANDT`, `AUFNR`, `AUFPL`, `APLAL`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0013.txt`
- `ziscs0005.txt`
- `ziscs0007.txt`
- `ziscs0007_gprs.txt`
- `ziscs0031.txt`
- `ziscs0039.txt`
- `ziscs0060.txt`
- `ziscs0287.txt`
- `ziscs0355.txt`
- `ziscs0465.txt`
- _...and 3 more_

---
### `ADCP`
**Description:** Address Communication — communication preferences
**References:** 24 SELECT statements | *20* programs
**Key Fields:** `CLIENT`, `ADDRNUMBER`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_get_crm_bp_info_02.txt`
- `z_inconsistent_address_delete.txt`
- `z_ossnote_436119.txt`
- `z_ossnote_436119_adrnum_pernum.txt`
- `z_ossnote_445575.txt`
- `zbacotype.txt`
- `zbaice001.txt`
- `zisbi0067.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- _...and 10 more_

---
### `VBFA`
**Description:** Sales Document Flow — document flow/log
**References:** 24 SELECT statements | *20* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`, `VBTYP_N`

**Join Paths:**
- Detected in WHERE: `ZO1`

**Programs Using This Table:**
- `zisfi0121.txt`
- `zisfi0238.txt`
- `zisfi0238_bw.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00019.txt`
- `zissd00020.txt`
- `zissd00058.txt`
- `zissd00059.txt`
- `zissd00060.txt`
- _...and 10 more_

---
### `USR01`
**Description:** User Address — user master address
**References:** 23 SELECT statements | *16* programs
**Key Fields:** `MANDT`, `BNAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_isdm_check_upper_limit.txt`
- `z_isdm_truncate_dec.txt`
- `z_isdm_truncate_dec_etdz.txt`
- `zbaicri02.txt`
- `zbaicri07.txt`
- `zca_doc.txt`
- `zficfdl02.txt`
- `zficfdl05.txt`
- `ziscs0261f01.txt`
- `zisdm0050.txt`
- _...and 6 more_

---
### `JCDS`
**Description:** Status Profile — status change log
**References:** 20 SELECT statements | *9* programs
**Key Fields:** `MANDT`, `OBJNR`, `STAT`, `INACT`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0173.txt`
- `ziscs0014.txt`
- `ziscs0014_adj.txt`
- `ziscs0039.txt`
- `ziscs0287.txt`
- `ziscs0340.txt`
- `ziscs0341.txt`
- `zisdm0080.txt`
- `zisdm0089.txt`

---
### `BSEG`
**Description:** Accounting Document Line — FI line item
**References:** 19 SELECT statements | *12* programs
**Key Fields:** `MANDT`, `BUKRS`, `BELNR`, `GJAHR`, `BUZEI`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbacbe034.txt`
- `zfchzuord_2.txt`
- `zggbs000.txt`
- `zisfi0029.txt`
- `zisfi0043.txt`
- `zisfi0083.txt`
- `zisfi0083_1.txt`
- `zisfi0083_1t.txt`
- `zisfi0083_2.txt`
- `zisfi0090.txt`
- _...and 2 more_

---
### `BNKA`
**Description:** Bank Master — bank details
**References:** 19 SELECT statements | *18* programs
**Key Fields:** `MANDT`, `BANKL`

**Join Paths:**
- Detected in WHERE: `BANKA, BANKL, BANKS, bankl, banks, loevm`

**Programs Using This Table:**
- `z_get_bank_name.txt`
- `ziscs0500.txt`
- `ziscs0800f01.txt`
- `ziscs0800i01.txt`
- `ziscs0802_f01.txt`
- `ziscs0815forms.txt`
- `ziscs0817forms.txt`
- `ziscsbnka_f01.txt`
- `zisfi0039.txt`
- `zisfi0051.txt`
- _...and 8 more_

---
### `CRHD`
**Description:** Work Center — work center definition
**References:** 18 SELECT statements | *16* programs
**Key Fields:** `MANDT`, `OBJID`

**Join Paths:**
- Detected in WHERE: `endda, kapid, lvorm, objid`

**Programs Using This Table:**
- `zisbi0104.txt`
- `ziscs0002.txt`
- `ziscs0003.txt`
- `ziscs0007.txt`
- `ziscs0007_gprs.txt`
- `ziscs0016.txt`
- `ziscs0026.txt`
- `ziscs0026a.txt`
- `ziscs0039.txt`
- `ziscs0046.txt`
- _...and 6 more_

---
### `EKET`
**Description:** Schedule Line — delivery schedule lines
**References:** 16 SELECT statements | *11* programs
**Key Fields:** `MANDT`, `EBELN`, `EBELP`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zissd00041.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00098.txt`
- `zmmpri000.txt`
- `zmmprsi01.txt`
- `zmmprsi13.txt`
- `zsdsoblk1.txt`
- `zsdsocbo1.txt`
- `zsdsodl01.txt`
- _...and 1 more_

---
### `EBAN`
**Description:** Purchase Requisition — purchase requisition
**References:** 16 SELECT statements | *9* programs
**Key Fields:** `MANDT`, `BANFN`, `BNFPO`

**Join Paths:**
- Detected in WHERE: `ADRN2, ADRNR, ADVCODE, AFNAM, AKTNR, ARSNR`

**Programs Using This Table:**
- `zissd00040.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00098.txt`
- `zissd00108.txt`
- `zmmprsi01.txt`
- `zmmprsi13.txt`

---
### `DD04L`
**Description:** Data Element — DDIC data element definitions
**References:** 16 SELECT statements | *3* programs
**Key Fields:** `FIELDNAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbacbe034.txt`
- `zbacbe106_ssa_cat.txt`
- `zjivs_rollname.txt`

---
### `DFKKCRH`
**Description:** Credit Management History — credit limit history
**References:** 14 SELECT statements | *11* programs
**Key Fields:** `MANDT`, `LAUFD`, `LAUFI`, `VKONT`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zficfdl04.txt`
- `ziscs0088.txt`
- `zisdm0104.txt`
- `zisdm0136.txt`
- `zisdm0136a.txt`
- `zisdm0136b.txt`
- `zisdm0136c.txt`
- `zisdm0136d.txt`
- `zisfi0025.txt`
- `zisfi0097.txt`
- _...and 1 more_

---
### `DFKKCRP`
**Description:** Credit Management — credit limit info
**References:** 14 SELECT statements | *9* programs
**Key Fields:** `MANDT`, `LAUFD`, `LAUFI`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zis_fi_calculate_cw.txt`
- `zisdm0104.txt`
- `zisfi0025.txt`
- `zisfi0088.txt`
- `zisfi0097.txt`
- `zisfi0101.txt`
- `zisfi0131.txt`
- `zisfi0147.txt`
- `zisfi0150.txt`

---
### `AGR_USERS`
**Description:** Authorization Group Users — role assignments
**References:** 14 SELECT statements | *12* programs
**Key Fields:** `MANDT`, `UNAME`, `AGR_NAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbacbe002.txt`
- `zbacbe034.txt`
- `zbacbe061.txt`
- `zbacbe062.txt`
- `zbacbe063.txt`
- `zbacbe064.txt`
- `zbacbe065.txt`
- `zbacbei04.txt`
- `ziscs0004f01.txt`
- `zisfi0166.txt`
- _...and 2 more_

---
### `DPAYP`
**Description:** Direct Debit Line — DD payment line item
**References:** 13 SELECT statements | *10* programs
**Key Fields:** `MANDT`, `LAUFD`, `LAUFZ`, `SEQNO`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_paymedium_cheque_refund.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zbacbt600.txt`
- `ziscs_migration_adjustment_m4.txt`
- `zisfi0028.txt`
- `zisfi0081.txt`
- `zisfi0099.txt`
- `zisfi0204.txt`
- `zisfi0238.txt`
- `zisfi0240.txt`

---
### `EASTI`
**Description:** SAP standard table
**References:** 12 SELECT statements | *6* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- Detected in WHERE: `AB, BIS, INDEXNR, LOGIKZW, indexnr, logikzw`

**Programs Using This Table:**
- `z_isdm_get_meter_relationship.txt`
- `zisdm0022_bulk.txt`
- `zisdm0024.txt`
- `zisdm0036.txt`
- `zisdm0216f01.txt`
- `zisdm0307.txt`

---
### `DFKKRD`
**Description:** Payment Request — payment request record
**References:** 12 SELECT statements | *7* programs
**Key Fields:** `MANDT`, `KEYZ1`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisfi0046.txt`
- `zisfi0103.txt`
- `zisfi0116.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test.txt`
- `zisfi0116_test2.txt`
- `zisfi0116_test3.txt`

---
### `DFKKCOH`
**Description:** Collection History — collection/payment history
**References:** 12 SELECT statements | *10* programs
**Key Fields:** `MANDT`, `VKONT`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0077.txt`
- `zisbi0083.txt`
- `zisbi0157.txt`
- `ziscs0124.txt`
- `ziscs0156.txt`
- `ziscs0437.txt`
- `zisfi0014.txt`
- `zisfi0025_corr_print.txt`
- `zisfi0198.txt`
- `zrdm_letter_2.txt`

---
### `AFKO`
**Description:** Order Header (CO) — cost order header
**References:** 12 SELECT statements | *11* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_bapi_get_ft_status.txt`
- `z_bapi_iia_dates_getlist.txt`
- `z_bapi_iia_dates_getlist_d.txt`
- `z_bapi_iia_get_detail.txt`
- `z_bapi_isusmorder_exch.txt`
- `ziscrm0318forms.txt`
- `ziscs0009.txt`
- `ziscs0154.txt`
- `ziscs0355.txt`
- `ziscseec_comm_frmwrk_trigger.txt`
- _...and 1 more_

---
### `DFKKRAPT`
**Description:** Payment Plan Installment — installment detail
**References:** 11 SELECT statements | *7* programs
**Key Fields:** `MANDT`, `OPBEL`

**Join Paths:**
- Detected in WHERE: `STDAT, augbt, augdt, opbel, opupk, opupw`

**Programs Using This Table:**
- `z_isbi_get_bill_invoice_docs.txt`
- `zisbi0040.txt`
- `zisbi0046.txt`
- `zisfi0028.txt`
- `zisfi0030.txt`
- `zisfi0037.txt`
- `zisfi0103.txt`

---
### `ETTIFB`
**Description:** Installation Billing Item — billing line items
**References:** 10 SELECT statements | *7* programs
**Key Fields:** `MANDT`, `ANLAGE`

**Join Paths:**
- Detected in WHERE: `anlage, bis, operand`

**Programs Using This Table:**
- `zisbi0016.txt`
- `zisbi0025.txt`
- `zisbi0025_1.txt`
- `zisbi0105.txt`
- `ziscs0049.txt`
- `ziscs_migration_unmetered_sp.txt`
- `zreprjt00.txt`

---
### `VBEP`
**Description:** Sales Document Schedule Line — delivery schedule
**References:** 10 SELECT statements | *7* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zissd00072.txt`
- `zissd00086.txt`
- `zissd00097.txt`
- `zissd00098.txt`
- `zsdsoblk1.txt`
- `zsdsoc001.txt`
- `zsdsocbo1.txt`

---
### `ERDO`
**Description:** Move-Out Contract — end of contract
**References:** 9 SELECT statements | *6* programs
**Key Fields:** `MANDT`, `VKONTO`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0041.txt`
- `zisbi0042.txt`
- `zisbi0042_ami.txt`
- `zisbi0042_newfm.txt`
- `zisbi0045.txt`
- `zreaexcep.txt`

---
### `BUT051`
**Description:** BP Relationship — BP-BP relationships
**References:** 9 SELECT statements | *3* programs
**Key Fields:** `CLIENT`, `PARTNER`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0224forms.txt`
- `ziscs0404.txt`
- `zisfi0038.txt`

---
### `ADRP`
**Description:** Address Person — person master data
**References:** 9 SELECT statements | *8* programs
**Key Fields:** `CLIENT`, `PERSNUMBER`

**Join Paths:**
- Detected in WHERE: `name_text, persnumber`

**Programs Using This Table:**
- `z_ossnote_445575.txt`
- `ziscv08_f01.txt`
- `ziscv08nv_f01.txt`
- `ziscv08nv_test_f01.txt`
- `zisdm0239f01.txt`
- `zissd00089_f01.txt`
- `zmmpre030s.txt`
- `zmmprsi01.txt`

---
### `EKBE`
**Description:** Purchasing History — goods receipt/invoice history
**References:** 9 SELECT statements | *6* programs
**Key Fields:** `MANDT`, `EBELN`, `EBELP`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `ziscs0120.txt`
- `zissd00027.txt`
- `zissd00038.txt`
- `zissd_recover_ekrs_for_ers.txt`
- `zmmpri001.txt`
- `zrepmir7.txt`

---
### `BSAS`
**Description:** Accounting Document (Cleared) — cleared G/L doc
**References:** 9 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `BUKRS`, `BELNR`, `GJAHR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zfchzuord_2.txt`

---
### `BSIS`
**Description:** Accounting Document (Open) — open G/L doc
**References:** 9 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `BUKRS`, `BELNR`, `GJAHR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zfchzuord_2.txt`

---
### `AGR_DEFINE`
**Description:** Authorization Group Definition — role definitions
**References:** 9 SELECT statements | *7* programs
**Key Fields:** `MANDT`, `AGR_NAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_role_set_masterlang.txt`
- `zbacbe062.txt`
- `zbacbe064.txt`
- `zbacbe065.txt`
- `zisfi0166.txt`
- `zissecrev.txt`
- `zmmpre030s.txt`

---
### `DFKKRH`
**Description:** Payment Request History — historical payment request
**References:** 7 SELECT statements | *4* programs
**Key Fields:** `MANDT`, `KEYZ1`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisfi0039.txt`
- `zisfi0088.txt`
- `zisfi0097.txt`
- `zisfi0131.txt`

---
### `DFKKCFRLS`
**Description:** SAP standard table
**References:** 7 SELECT statements | *7* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisfi0046.txt`
- `zisfi0103.txt`
- `zisfi0116.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test.txt`
- `zisfi0116_test2.txt`
- `zisfi0116_test3.txt`

---
### `BUT100`
**Description:** SAP standard table
**References:** 7 SELECT statements | *4* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `ziscrm0036.txt`
- `ziscrm0037.txt`
- `ziscs0023.txt`
- `ziscs0193.txt`

---
### `ERCHO`
**Description:** SAP standard table
**References:** 6 SELECT statements | *5* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- Detected in WHERE: `belnr, validation`

**Programs Using This Table:**
- `zbildocaut.txt`
- `zisbi0041.txt`
- `zisbi0214f01.txt`
- `zisdm0172.txt`
- `zreaexcep.txt`

---
### `EITR`
**Description:** Technical Installation — technical location assignment
**References:** 6 SELECT statements | *5* programs
**Key Fields:** `MANDT`, `ILOA`, `EQUNR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0027.txt`
- `zisbi0045.txt`
- `zisbi0048.txt`
- `zisbi0091.txt`
- `zisbifixeitr.txt`

---
### `DD01L`
**Description:** Data Type — ABAP data type definitions
**References:** 6 SELECT statements | *4* programs
**Key Fields:** `TABNAME`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbacbe034.txt`
- `zbacbe106_ssa_cat.txt`
- `zjivs_rollname.txt`
- `zjivs_set_export_selections.txt`

---
### `BSAK`
**Description:** Accounting Document (Cleared) — cleared vendor doc
**References:** 5 SELECT statements | *2* programs
**Key Fields:** `MANDT`, `BUKRS`, `LIFNR`, `BELNR`, `GJAHR`

**Join Paths:**
- Detected in WHERE: `LIFNR`

**Programs Using This Table:**
- `zbacbe034.txt`
- `zfchzuord_2.txt`

---
### `BSIK`
**Description:** Accounting Document (Open) — open vendor doc
**References:** 5 SELECT statements | *2* programs
**Key Fields:** `MANDT`, `BUKRS`, `LIFNR`, `BELNR`, `GJAHR`

**Join Paths:**
- Detected in WHERE: `LIFNR`

**Programs Using This Table:**
- `zbacbe034.txt`
- `zfchzuord_2.txt`

---
### `CAUFV`
**Description:** Order (All) — combined order view
**References:** 5 SELECT statements | *3* programs
**Key Fields:** `MANDT`, `AUFNR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `ziscs0252f01.txt`
- `zisdm0018.txt`
- `zisdm0019.txt`

---
### `VBUP`
**Description:** Sales Document Item Status — item status
**References:** 4 SELECT statements | *4* programs
**Key Fields:** `MANDT`, `VBELN`, `POSNR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zissd00012.txt`
- `zissd00024.txt`
- `zsdisqry03.txt`
- `zsdisqry04.txt`

---
### `BSAD`
**Description:** Accounting Document (Cleared) — cleared customer doc
**References:** 3 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `BUKRS`, `BELNR`, `GJAHR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zfchzuord_2.txt`

---
### `BSID`
**Description:** Accounting Document (Open) — open customer doc
**References:** 3 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `BUKRS`, `KUNNR`, `BELNR`, `GJAHR`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zfchzuord_2.txt`

---
### `DD07L`
**Description:** Fixed Values — domain fixed values
**References:** 3 SELECT statements | *3* programs
**Key Fields:** `DOMNAME`, `DDTEXT`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `ziscs0083.txt`
- `zisfi0197.txt`
- `zisfi0197_smis.txt`

---
### `BUT021`
**Description:** BP Tax Number — tax ID numbers for BP
**References:** 2 SELECT statements | *2* programs
**Key Fields:** `CLIENT`, `PARTNER`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `z_inconsistent_address_delete.txt`
- `ziscs0189.txt`

---
### `VBUK`
**Description:** Sales Document Status — status header
**References:** 2 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `VBELN`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zissd00113.txt`

---
### `AFVC`
**Description:** Operation — order operation/activity
**References:** 2 SELECT statements | *2* programs
**Key Fields:** `MANDT`, `AUFNR`, `AUFPL`, `APLAL`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zbapi_iia_dates_getlist.txt`
- `ziscsriaufk20.txt`

---
### `COBRB`
**Description:** Contract Type — contract category definitions
**References:** 2 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `VTYPK`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `ziscsriaufk20.txt`

---
### `EADRREGAREA`
**Description:** SAP standard table
**References:** 1 SELECT statements | *1* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisbi0007.txt`

---
### `DFKKZPT`
**Description:** SAP standard table
**References:** 1 SELECT statements | *1* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisfi_pylot_del.txt`

---
### `DFKKLOCKH`
**Description:** Lock History — lock status history
**References:** 1 SELECT statements | *1* programs
**Key Fields:** `MANDT`, `LOOBJ1`, `LOTYP`

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zisfi0162.txt`

---
### `BSEC`
**Description:** SAP standard table
**References:** 1 SELECT statements | *1* programs
**Key Fields:** _unknown_ (please verify in SE11)

**Join Paths:**
- _no join paths detected in CCMS code_

**Programs Using This Table:**
- `zfchzuord_2.txt`

---

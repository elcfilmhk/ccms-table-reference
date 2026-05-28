# ZISCSRETCODES_WITH_KEYS
**Description:** ZISCSRETCODES with Keys
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_acb_get_ca_sms==============ft`
- `z_bapi_web_antispam===========ft`
- `z_bapi_webid_forget===========ft`
- `z_get_emo_premise_address=====ft`
- `z_iscsget_pref_comm_chnl======ft`
- `z_iscspcchoicequotacalc=======ft`
- `zcl_z_test_jlc6259_mpc`
- `zcl_ziscspc_ngo_sea_07_mpc`
- `zcl_ztest_get_cons_mpc`
- `zcl_zziscs_pc_ngo_sear_mpc`
- `ziscrmact_queue===============ft`
- `ziscrmact_send================ft`
- `ziscrmact_send_job`
- `ziscs0005`
- `ziscs0151`
- `ziscs0151_get_acc_balance=====ft`
- `ziscs0151_get_contacts========ft`
- `ziscs0208`
- `ziscs0383_eec`
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0390_eec`
- `ziscs0391_eec`
- `ziscs0392_eec`
- `ziscs0398_eec`
- `ziscs0407`
- `ziscs0408`
- `ziscs0473_eec`
- `ziscs0475_eec`
- `ziscs0483`
- `ziscs0512`
- `ziscs0725`
- `ziscs0800`
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscs0841`
- `ziscs0843`
- `ziscs1031`
- `ziscs_col_sel_get_columns=====ft`
- `ziscs_crm_get_bp_contacts=====ft`
- `ziscs_get_email_template======ft`
- `ziscs_pon_ca_scr`
- `ziscs_pon_export_ca`
- `ziscs_pon_get_ca==============ft`
- `ziscs_pon_import_sent_hist`
- `ziscs_refresh_cont_bp=========ft`
- `ziscs_rep_log_exec============ft`
- `ziscs_rep_log_exec_end========ft`
- `ziscs_web_create_tcall========ft`
- `ziscs_web_create_tcall_ws=====ft`
- `ziscseec_ca_recalc_part_index=ft`
- `ziscseec_check_mkt_consent====ft`
- `ziscseec_eher_get_opt_inout===ft`
- `ziscseec_eher_set_opt_inout===ft`
- `ziscseec_eo_get_eligible_ca===ft`
- `ziscseec_ep_conversion_create=ft`
- `ziscseec_ep_order_save========ft`
- `ziscseec_ep_redeem============ft`
- `ziscseec_ep_redeem_ws=========ft`
- `ziscseec_ep_trans_create======ft`
- `ziscseec_ep_trans_reas_check==ft`
- `ziscseec_gen_eher_rpt=========ft`
- `ziscseec_get_adjacent_bills===ft`
- `ziscseec_get_benmark_ca_detailft`
- `ziscseec_get_billed_kwh=======ft`
- `ziscseec_get_ca_contract======ft`
- `ziscseec_get_ca_email=========ft`
- `ziscseec_week_sav_calc========ft`
- `ziscseec_week_sav_get_rs======ft`
- `ziscseec_week_sav_get_rs_ws===ft`
- `ziscspc_is_registered=========ft`
- `ziscspc_opt_out===============ft`
- `ziscv_datamask1`
- `ziscv_datamask1_thread`
- `ziscv_datamask_thread=========ft`
- `ziscv_datamask_thread_ws======ft`
- `ziscv_dmask_custom_fm_sample==ft`
- `ziscv_field_person_name=======ft`
- `zisdm0337`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisfi0305`
- `zrca_ssr_cust_extract`
- `zrca_ssr_extract`
- `zziscv_datamask1`
- `zziscv_datamask1_thread`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `KEY1` | CHAR | 40 |  | Character field of length 40 |
| 2 | `KEY2` | CHAR | 40 |  | Character field of length 40 |
| 3 | `KEY3` | CHAR | 40 |  | Character field of length 40 |
| 4 | `KEY4` | CHAR | 40 |  | Character field of length 40 |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Customized structure for return code |
| 6 | `TYPE` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 7 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 8 | `MESSAGE` | CHAR | 220 |  | Message Text |

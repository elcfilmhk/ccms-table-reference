# ZISCSRETCODES
**Description:** Customized structure for return code
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_generate_p_notify_ws===ft`
- `z_bapi_login_low==============ft`
- `z_bapi_pyl_coupon_pre_token===ft`
- `z_bapi_pyl_login_new==========ft`
- `z_bapi_pyl_registration=======ft`
- `z_iscs_create_meter_so_notif==ft`
- `z_isdm_comp_meter_reg=========ft`
- `z_isdm_get_meter_reg==========ft`
- `z_isdm_meter_removal==========ft`
- `z_isdm_mol_map_fc_loc=========ft`
- `z_vdip_enq_gen_letter=========ft`
- `z_vdip_enq_gen_letter_ws======ft`
- `z_vdip_enq_get_cases==========ft`
- `z_vdip_enq_get_cases_ws=======ft`
- `z_vdip_enq_get_figures_ws=====ft`
- `z_vdip_enq_get_workdates_ws===ft`
- `z_vdip_enq_save_cases_ws======ft`
- `z_vdip_enq_set_status_ws======ft`
- `z_voltdip_send_reminder=======ft`
- `zcl_ziscseec_ep_trans__mpc`
- `zisbi0199`
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `zisbi_print_vdipe_lttr========ft`
- `ziscrm0318`
- `ziscs0015`
- `ziscs0369_pyl`
- `ziscs0382_eec`
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0390_eec`
- `ziscs0396_eec`
- `ziscs0404`
- `ziscs0408`
- `ziscs0460`
- `ziscs0470_eec`
- `ziscs0475_eec`
- `ziscs0478_eec`
- `ziscs0479_eec`
- `ziscs0494`
- `ziscs0726`
- `ziscs0730`
- `ziscs0806`
- `ziscs0811`
- `ziscs0812`
- `ziscs0818`
- `ziscs0824`
- `ziscs0826`
- `ziscs_eml_trk_conv_vkont======ft`
- `ziscs_eml_trk_csv_map_vals====ft`
- `ziscs_eml_trk_csv_row_to_val==ft`
- `ziscs_eml_trk_email_to_tk=====ft`
- `ziscs_eml_trk_ev_search=======ft`
- `ziscs_eml_trk_gen_guid========ft`
- `ziscs_eml_trk_get_eml_addr_tk=ft`
- `ziscs_eml_trk_rdc_get_hd_id===ft`
- `ziscs_eml_trk_rdcdt_to_dt=====ft`
- `ziscs_eml_trk_split_csv_row===ft`
- `ziscs_eml_trk_split_rdc_headerft`
- `ziscs_pon_ca_scr`
- `ziscs_send_email_bcs==========ft`
- `ziscs_send_email_radica=======ft`
- `ziscs_voltdip_send_reminder`
- `ziscseec_ca_achv_maintain=====ft`
- `ziscseec_ca_achv_maintain_ws==ft`
- `ziscseec_ca_action_complete===ft`
- `ziscseec_ca_action_complete_wsft`
- `ziscseec_eml_postman_radica`
- `ziscseec_eo_benchmark_ca======ft`
- `ziscseec_eo_benchmark_ca_ws===ft`
- `ziscseec_eo_cons_comparison===ft`
- `ziscseec_eo_cons_comparison_wsft`
- `ziscseec_eo_gen_token=========ft`
- `ziscseec_eo_gen_token_ws======ft`
- `ziscseec_eo_get_ca_profile====ft`
- `ziscseec_eo_get_ca_profile_ws=ft`
- `ziscseec_eo_get_txt===========ft`
- `ziscseec_eo_get_txt_tk_ws=====ft`
- `ziscseec_eo_get_txt_ws========ft`
- `ziscseec_eo_hea_pie_ws========ft`
- `ziscseec_eo_login=============ft`
- `ziscseec_eo_login_ws==========ft`
- `ziscseec_eo_save_ca_contact===ft`
- `ziscseec_eo_save_ca_contact_wsft`
- `ziscseec_ep_get_balance=======ft`
- `ziscseec_ep_get_balance_ws====ft`
- `ziscseec_ep_get_quiz_ws=======ft`
- `ziscseec_ep_trans_search======ft`
- `ziscseec_ep_trans_search_ws===ft`
- `ziscseec_get_ca_attr==========ft`
- `ziscseec_get_ca_bengrp========ft`
- `ziscseec_get_eher_settings====ft`
- `ziscseec_get_period_consump===ft`
- `ziscseec_get_queans===========ft`
- `ziscseec_get_queans_ws========ft`
- `ziscseec_get_txt==============ft`
- `ziscseec_last_yr_same_bill====ft`
- `ziscseec_queue_email==========ft`
- `ziscseec_resolve_token_ws=====ft`
- `ziscseec_save_answers_ws======ft`
- `ziscseec_save_eher_settings===ft`
- `ziscspc_bapi_login_low========ft`
- `zisdm0286`
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TYPE` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 2 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 3 | `MESSAGE` | CHAR | 220 |  | Message Text |

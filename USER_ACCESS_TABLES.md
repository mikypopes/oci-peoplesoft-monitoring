$ sqlplus "/as sysdba"

CREATE USER appsro IDENTIFIED BY appsro DEFAULT TABLESPACE &some_tb;
GRANT connect, resource, select any dictionary TO appsro;
GRANT SELECT on sysadm.ps_loan_stdnt_awd TO APPSRO;
GRANT SELECT on sysadm.ps_loan_orig_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_loan_orignatn TO APPSRO;
GRANT SELECT on sysadm.ps_aid_year_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_pay_calendar TO APPSRO;
GRANT SELECT on sysadm.ps_pay_check TO APPSRO;
GRANT SELECT on sysadm.ps_pay_oth_earns TO APPSRO;
GRANT SELECT on sysadm.ps_earnings_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_sf_acctg_ln TO APPSRO;
GRANT SELECT on sysadm.ps_eo_msgbatprm TO APPSRO;
GRANT SELECT on sysadm.ps_item_line_sf TO APPSRO;
GRANT SELECT on sysadm.ps_item_sf TO APPSRO;
GRANT SELECT on sysadm.ps_stdnt_awrd_disb TO APPSRO;
GRANT SELECT on sysadm.ps_stdnt_fa_term TO APPSRO;
GRANT SELECT on sysadm.ps_acad_plan TO APPSRO;
GRANT SELECT on sysadm.ps_acad_degr_plan TO APPSRO;
GRANT SELECT on sysadm.ps_item_type_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_payment_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_set_cntrl_rec TO APPSRO;
GRANT SELECT on sysadm.ps_bus_unit_tbl_sf TO APPSRO;
GRANT SELECT on sysadm.ps_installation TO APPSRO;
GRANT SELECT on sysadm.ps_stdnt_awards TO APPSRO;
GRANT SELECT on sysadm.ps_disb_id_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_tl_exception TO APPSRO;
GRANT SELECT on sysadm.ps_tl_except_defn TO APPSRO;
GRANT SELECT on sysadm.ps_ben_defn_plan TO APPSRO;
GRANT SELECT on sysadm.ps_ben_defn_pgm TO APPSRO;
GRANT SELECT on sysadm.ps_ben_defn_optn TO APPSRO;
GRANT SELECT on sysadm.ps_ben_defn_cost TO APPSRO;
GRANT SELECT on sysadm.ps_doc_type_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_jrnl_code_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_installation_fs TO APPSRO;
GRANT SELECT on sysadm.ps_seq_range_detl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_array TO APPSRO;
GRANT SELECT on sysadm.ps_gp_array_fld TO APPSRO;
GRANT SELECT on sysadm.ps_gp_pin TO APPSRO;
GRANT SELECT on sysadm.psdbfield TO APPSRO;
GRANT SELECT on sysadm.psrecdefn TO APPSRO;
GRANT SELECT on sysadm.ps_proj_resource TO APPSRO;
GRANT SELECT on sysadm.psprcsrqst TO APPSRO;
GRANT SELECT on sysadm.ps_ca_bill_plan TO APPSRO;
GRANT SELECT on sysadm.ps_gp_wa_array TO APPSRO;
GRANT SELECT on sysadm.ps_gp_wa_fld TO APPSRO;
GRANT SELECT on sysadm.psrecfieldall TO APPSRO;
GRANT SELECT on sysadm.ps_gp_run_type_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_fc_tbl TO APPSRO;
GRANT SELECT on sysadm.psoprdefn TO APPSRO;
GRANT SELECT on sysadm.ps_fs_cf_act_log TO APPSRO;
GRANT SELECT on sysadm.psprojectitem TO APPSRO;
GRANT SELECT on sysadm.psapmsgpubhdr TO APPSRO;
GRANT SELECT on sysadm.psqueuedefn TO APPSRO;
GRANT SELECT on sysadm.psapmsgdomstat TO APPSRO;
GRANT SELECT on sysadm.psapmsgpubcon TO APPSRO;
GRANT SELECT on sysadm.psapmsgsubcon TO APPSRO;
GRANT SELECT on sysadm.ps_gp_cal_run TO APPSRO;
GRANT SELECT on sysadm.ps_gp_cal_run_strm TO APPSRO;
GRANT SELECT on sysadm.ps_gp_strm TO APPSRO;
GRANT SELECT on sysadm.ps_voucher TO APPSRO;
GRANT SELECT on sysadm.ps_ca_acctplan TO APPSRO;
GRANT SELECT on sysadm.ps_pay_form_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_loan_disb_msg TO APPSRO;
GRANT SELECT on sysadm.ps_hr_dr_control TO APPSRO;
GRANT SELECT on sysadm.ps_ss_link_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_hr_dr_ui_cfg TO APPSRO;
GRANT SELECT on sysadm.pstzoffset TO APPSRO;
GRANT SELECT on sysadm.ps_po_itm_stg TO APPSRO;
GRANT SELECT on sysadm.ps_tl_time_periods TO APPSRO;
GRANT SELECT on sysadm.ps_tl_calendar TO APPSRO;
GRANT SELECT on sysadm.ps_gp_formula TO APPSRO;
GRANT SELECT on sysadm.ps_class_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_term_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_stdnt_enrl TO APPSRO;
GRANT SELECT on sysadm.ps_ledger TO APPSRO;
GRANT SELECT on sysadm.ps_open_trans TO APPSRO;
GRANT SELECT on sysadm.ps_fsa_benefit TO APPSRO;
GRANT SELECT on sysadm.ps_fsa_benef_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_fed_tax_data TO APPSRO;
GRANT SELECT on sysadm.ps_state_tax_data TO APPSRO;
GRANT SELECT on sysadm.ps_ssr_he_rep_prds TO APPSRO;
GRANT SELECT on sysadm.ps_saa_arslt_rqvw TO APPSRO;
GRANT SELECT on sysadm.ps_saa_adb_report TO APPSRO;
GRANT SELECT on sysadm.ps_institution_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_pay_earnings TO APPSRO;
GRANT SELECT on sysadm.ps_gp_process TO APPSRO;
GRANT SELECT on sysadm.ps_gp_process_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_section_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_elem_grp_mbr TO APPSRO;
GRANT SELECT on sysadm.ps_stdnt_awd_pkg TO APPSRO;
GRANT SELECT on sysadm.ps_gp_system_pin TO APPSRO;
GRANT SELECT on sysadm.psrecfield TO APPSRO;
GRANT SELECT on sysadm.ps_tl_dates_tbl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_pintree_vw TO APPSRO;
GRANT SELECT on sysadm.ps_gp_pye_prc_stat TO APPSRO;
GRANT SELECT on sysadm.ps_gp_rto_trgr TO APPSRO;
GRANT SELECT on sysadm.ps_gp_rto_evt TO APPSRO;
GRANT SELECT on sysadm.ps_gp_iter_trgr TO APPSRO;
GRANT SELECT on sysadm.ps_gp_formula_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_pye_sect_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_taxform_box TO APPSRO;
GRANT SELECT on sysadm.pswebprofnvp TO APPSRO;
GRANT SELECT on sysadm.pswebprofhist TO APPSRO;
GRANT SELECT on sysadm.ps_po_hdr TO APPSRO;
GRANT SELECT on sysadm.ps_vchr_acctg_line TO APPSRO;
GRANT SELECT on sysadm.ps_pymnt_vchr_xref TO APPSRO;
GRANT SELECT on sysadm.ps_ecintlink TO APPSRO;
GRANT SELECT on sysadm.ps_ecexttplink TO APPSRO;
GRANT SELECT on sysadm.ps_ecqueue TO APPSRO;
GRANT SELECT on sysadm.psoptions TO APPSRO;
GRANT SELECT on sysadm.psaeappldefn TO APPSRO;
GRANT SELECT on sysadm.psaeappltemptbl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_array_key TO APPSRO;
GRANT SELECT on sysadm.ps_cbr_partic TO APPSRO;
GRANT SELECT on sysadm.ps_cobra_event TO APPSRO;
GRANT SELECT on sysadm.ps_cbr_partic_plan TO APPSRO;
GRANT SELECT on sysadm.ps_cbr_partic_optn TO APPSRO;
GRANT SELECT on sysadm.ps_cbr_partic_dpnd TO APPSRO;
GRANT SELECT on sysadm.ps_local_tax_data TO APPSRO;
GRANT SELECT on sysadm.ps_job TO APPSRO;
GRANT SELECT on sysadm.ps_gp_payee_data TO APPSRO;
GRANT SELECT on sysadm.ps_personal_data TO APPSRO;
GRANT SELECT on sysadm.ps_ex_sheet_hdr TO APPSRO;
GRANT SELECT on sysadm.ps_ex_sheet_line TO APPSRO;
GRANT SELECT on sysadm.ps_ex_tauth_hdr TO APPSRO;
GRANT SELECT on sysadm.ps_ex_tauth_line TO APPSRO;
GRANT SELECT on sysadm.ps_ex_adv_hdr TO APPSRO;
GRANT SELECT on sysadm.ps_ex_adv_line TO APPSRO;
GRANT SELECT on sysadm.ps_ex_time_hdr TO APPSRO;
GRANT SELECT on sysadm.ps_ex_time_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_aid_yr_car_term TO APPSRO;
GRANT SELECT on sysadm.ps_gp_calendar TO APPSRO;
GRANT SELECT on sysadm.ps_gp_run_type TO APPSRO;
GRANT SELECT on sysadm.ps_gp_cal_prd TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_ids TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_stepinst TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_userinst TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_stage TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_timeout TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_timeoutdef TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_ntf_prnt TO APPSRO;
GRANT SELECT on sysadm.ps_eoaw_auth_dtl TO APPSRO;
GRANT SELECT on sysadm.ps_gp_pinmap_effdt TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_cost TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_optn TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_plan TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_dpnd TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_invt TO APPSRO;
GRANT SELECT on sysadm.ps_bas_partic_elig TO APPSRO;
GRANT SELECT on sysadm.ps_gp_elem_grp TO APPSRO;
GRANT SELECT on sysadm.psxlatitem TO APPSRO;
GRANT SELECT on sysadm.ps_gp_elig_grp_mbr TO APPSRO;
GRANT SELECT on sysadm.ps_gp_eln_set_lst TO APPSRO;
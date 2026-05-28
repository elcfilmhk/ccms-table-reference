# ZISCSPC_CUSTREG
**Description:** Transaction Table for Customer Registration Data
**Total Fields:** 25
**Key Fields:** MANDT, PROG_ID, REG_ID

## Programs Using This Table
- `zcl_ziscspc_upd_custre_dpc_ext`
- `zdisp`
- `ziscs0727`
- `ziscs0806`
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscs0809`
- `ziscs0809a`
- `ziscs0824`
- `ziscs1031`
- `ziscs1033`
- `ziscs1034`
- `ziscs_migration_scm_3_5`
- `ziscs_migration_scm_4`
- `ziscs_pc_custreg==============ft`
- `ziscs_pc_custreg_det==========ft`
- `ziscs_pc_custreg_welgiftcheck=ft`
- `ziscspc_comm_frmwrk_trigger===ft`
- `ziscspc_eec_action_badges`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `REG_ID` | CHAR | 10 | 🔑 | Registration ID |
| 4 | `VALIDFROM` | DATS | 8 |  | Valid From Date |
| 5 | `VALIDTO` | DATS | 8 |  | Valid To Date |
| 6 | `CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 7 | `EMAILID` | CHAR | 100 |  | Customer Email ID |
| 8 | `CONTACT` | CHAR | 8 |  | Contact Number |
| 9 | `PROD_ID` | CHAR | 3 |  | Product ID |
| 10 | `SPECIAL_CODE` | CHAR | 20 |  | Special Code |
| 11 | `QRCODE` | CHAR | 50 |  | QR Code |
| 12 | `QRCODEVALID` | DATS | 8 |  | Valid To Date |
| 13 | `STATUS` | CHAR | 1 |  | Status for Merchant in PC |
| 14 | `BEN_ID` | CHAR | 2 |  | Beneficiary ID |
| 15 | `ES_CODE` | CHAR | 1 |  | Energy Saving Code |
| 16 | `DELETION_IND` | CHAR | 1 |  | Deletion Indicator |
| 17 | `WEL_GIFT` | CHAR | 2 |  | Welcome Gift |
| 18 | `SOURCE` | CHAR | 1 |  | Source |
| 19 | `SELF_INIT` | CHAR | 1 |  | Self-initiated |
| 20 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 21 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 22 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 23 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 24 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 25 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |

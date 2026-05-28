# ZISCS_VDIPE_LETTER_WS
**Description:** Input Struct for VoltDipEnquiry Letter via WebService
**Total Fields:** 16
**Key Fields:** _none_

## Programs Using This Table
- `z_vdip_enq_gen_letter=========ft`
- `z_vdip_enq_gen_letter_ws======ft`
- `zcl_z_vdip_enq_gen_let_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `COMP_NAME` | CHAR | 100 |  | Company Name of customer |
| 2 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 3 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 4 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 5 | `STREET` | CHAR | 60 |  | Street |
| 6 | `CITY2` | CHAR | 40 |  | District |
| 7 | `CITY1` | CHAR | 40 |  | City |
| 8 | `LTTR_RCPT_NAME` | CHAR | 100 |  | Recipient Name as displayed on letter |
| 9 | `LTTR_REF` | CHAR | 80 |  | Reference Number as displayed on letter |
| 10 | `LTTR_SUBJ_TEXT` | CHAR | 200 |  | Letter Subject Header Text |
| 11 | `INCD_VOLT_LV` | CHAR | 50 |  | Voltage Level text as displayed on letter |
| 12 | `INCD_DT` | CHAR | 14 |  | Investigation Result: Incident datetime |
| 13 | `LTTR_ACC_MGR_NAME` | CHAR | 100 |  | AM name as displayed on letter |
| 14 | `LTTR_ACC_MGR_TEL` | CHAR | 30 |  | AM Telephone as displayed on letter |
| 15 | `CASE_ID` | NUMC | 8 |  | VoltDipEnquiry case ID |
| 16 | `LANG` | LANG | 1 |  | Language Key |

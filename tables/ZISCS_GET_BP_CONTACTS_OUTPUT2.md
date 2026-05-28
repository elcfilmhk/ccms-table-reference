# ZISCS_GET_BP_CONTACTS_OUTPUT2
**Description:** Output Structure of FM ZISCS_CRM_GET_BP_CONTACTS
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0151`
- `ziscs0841`
- `ziscs_crm_get_bp_contacts=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `PARTNERGUID` | RAW | 16 |  | Business Partner GUID |
| 3 | `CHANNEL` | CHAR | 3 |  | Marketing Permission: Communication Channel |
| 4 | `PERMISSION` | NUMC | 3 |  | Marketing Permission: Consent |
| 5 | `ORIGIN` | CHAR | 3 |  | Marketing Permission: Form of Consent |
| 6 | `VALID_FROM` | DATS | 8 |  | Marketing Permission: Date of Consent |
| 7 | `BP_TEL_STD` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 8 | `BP_MOB_STD` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 9 | `BP_FAX_STD` | CHAR | 30 |  | Fax number: dialling code+number |
| 10 | `BP_EML_STD` | CHAR | 241 |  | E-Mail Address |
| 11 | `BP_TEL_STD_ISU` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 12 | `BP_MOB_STD_ISU` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 13 | `BP_FAX_STD_ISU` | CHAR | 30 |  | Fax number: dialling code+number |
| 14 | `BP_EML_STD_ISU` | CHAR | 241 |  | E-Mail Address |

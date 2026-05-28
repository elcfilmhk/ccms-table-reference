# ZISCS_EEC_EO_CA_PROFILE
**Description:** EE&C CA Profile as needed by EcoOptimizer
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0386_eec`
- `ziscs0390_eec`
- `ziscs0475_eec`
- `ziscseec_eo_get_ca_profile====ft`
- `ziscseec_eo_get_ca_profile_ws=ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `REG_NAME` | CHAR | 100 |  | Text (100 characters) |
| 3 | `DISPLAY_NAME` | CHAR | 100 |  | Text (100 characters) |
| 4 | `EML_LIST` | TTYP | 0 |  | Table of ZISCS_EEC_EO_CA_PROF_EML |
| 5 | `CONTACT_NUMBER` | CHAR | 100 |  | Text (100 characters) |
| 6 | `ACCEPTED_TERMS_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `PREFERRED_LANG` | LANG | 1 |  | Language in connection with the contract account |
| 8 | `STAFF` | CHAR | 1 |  | Single-Character Flag |
| 9 | `MKT_CONSENT` | CHAR | 1 |  | 'Y': Given; 'N': Rejected; others: Not Specified |
| 10 | `MKT_CONSENT_EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 11 | `EP360_QUIZ1_COMPLETED` | CHAR | 1 |  | Single-Character Flag |
| 12 | `DSM_DETAILS` | TTYP | 0 |  | table type for DSM Details |

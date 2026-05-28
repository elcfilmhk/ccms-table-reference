# ZBW_CRM_BPADRC_ATTR
**Description:** BW Extract Structure - Business Partner Address
**Total Fields:** 76
**Key Fields:** _none_

## Programs Using This Table
- `z_bw_extract_bpadrc===========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `ADRNB` | CHAR | 10 |  | Address Number |
| 3 | `ZZSTREET_SUPP2` | CHAR | 40 |  | Street 3 |
| 4 | `ZZSTREET_SUPP1` | CHAR | 40 |  | Street 2 |
| 5 | `ZZSTREET` | CHAR | 60 |  | Street |
| 6 | `ZZHOUSE_NUM` | CHAR | 10 |  | House Number |
| 7 | `ZZCITY2` | CHAR | 40 |  | District |
| 8 | `ZZCITY1` | CHAR | 40 |  | City |
| 9 | `ZZCOUNTRY` | CHAR | 3 |  | Country Key |
| 10 | `ZZPOST_CODE1` | CHAR | 10 |  | City postal code |
| 11 | `ZZSTREET_SUPP2_C` | CHAR | 40 |  | Street 3 (Chinese) |
| 12 | `ZZSTREET_SUPP1_C` | CHAR | 40 |  | Street 2 (Chinese) |
| 13 | `ZZSTREET_C` | CHAR | 60 |  | Street (Chinese) |
| 14 | `ZZHOUSE_NUM_C` | CHAR | 10 |  | House Number (Chinese) |
| 15 | `ZZCITY2_C` | CHAR | 40 |  | District (Chinese) |
| 16 | `ZZCITY1_C` | CHAR | 40 |  | City (Chinese) |
| 17 | `ZZCOUNTRY_C` | CHAR | 3 |  | Country Key (Chinese) |
| 18 | `ZZPOST_CODE1_C` | CHAR | 10 |  | City Postal Code (Chinese) |
| 19 | `ZZCHDAT` | DATS | 8 |  | Date when object was last changed |
| 20 | `ZZCRDAT` | DATS | 8 |  | Date on which the object was created |
| 21 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 22 | `ZZDEP_PHO_CNTY1` | CHAR | 3 |  | Dependent telephone country 1 |
| 23 | `ZZDEP_PHO_CNTY2` | CHAR | 3 |  | Dependent telephone country 2 |
| 24 | `ZZDEP_PHO_CNTY3` | CHAR | 3 |  | Dependent telephone country 3 |
| 25 | `ZZDEP_PHO_TEL1` | CHAR | 30 |  | Dependent telephone 1 |
| 26 | `ZZDEP_PHO_TEL2` | CHAR | 30 |  | Dependent telephone 2 |
| 27 | `ZZDEP_PHO_TEL3` | CHAR | 30 |  | Dependent telephone 3 |
| 28 | `ZZDEP_PHO_EXT1` | CHAR | 10 |  | Dependent telephone extension 1 |
| 29 | `ZZDEP_PHO_EXT2` | CHAR | 10 |  | Dependent telephone extension 2 |
| 30 | `ZZDEP_PHO_EXT3` | CHAR | 10 |  | Dependent telephone extension 3 |
| 31 | `ZZDEP_PHO_NOT1` | CHAR | 1 |  | Flag: Dependent Telephone Not Used 1 |
| 32 | `ZZDEP_PHO_NOT2` | CHAR | 1 |  | Flag: Dependent Telephone Not Used 2 |
| 33 | `ZZDEP_PHO_NOT3` | CHAR | 1 |  | Flag: Dependent Telephone Not Used 3 |
| 34 | `ZZDEP_PHO_RMK1` | CHAR | 50 |  | Dependent Telephone Remark 1 |
| 35 | `ZZDEP_PHO_RMK2` | CHAR | 50 |  | Dependent Telephone Remark 2 |
| 36 | `ZZDEP_PHO_RMK3` | CHAR | 50 |  | Dependent Telephone Remark 3 |
| 37 | `ZZDEP_MPHO_CNTY1` | CHAR | 3 |  | Dependent mobile country 1 |
| 38 | `ZZDEP_MPHO_CNTY2` | CHAR | 3 |  | Dependent mobile country 2 |
| 39 | `ZZDEP_MPHO_CNTY3` | CHAR | 3 |  | Dependent mobile country 3 |
| 40 | `ZZDEP_MPHO_TEL1` | CHAR | 30 |  | Dependent mobile 1 |
| 41 | `ZZDEP_MPHO_TEL2` | CHAR | 30 |  | Dependent mobile 2 |
| 42 | `ZZDEP_MPHO_TEL3` | CHAR | 30 |  | Dependent mobile 3 |
| 43 | `ZZDEP_MPHO_EXT1` | CHAR | 10 |  | Dependent mobile extension 1 |
| 44 | `ZZDEP_MPHO_EXT2` | CHAR | 10 |  | Dependent mobile extension 2 |
| 45 | `ZZDEP_MPHO_EXT3` | CHAR | 10 |  | Dependent mobile extension 3 |
| 46 | `ZZDEP_MPHO_NOT1` | CHAR | 1 |  | Flag: Dependent Mobile Not Used 1 |
| 47 | `ZZDEP_MPHO_NOT2` | CHAR | 1 |  | Dependent Mobile Not Used 2 |
| 48 | `ZZDEP_MPHO_NOT3` | CHAR | 1 |  | Dependent Mobile Not Used 3 |
| 49 | `ZZDEP_MPHO_RMK1` | CHAR | 50 |  | Dependent Mobile Remark 1 |
| 50 | `ZZDEP_MPHO_RMK2` | CHAR | 50 |  | Dependent Mobile Remark 2 |
| 51 | `ZZDEP_MPHO_RMK3` | CHAR | 50 |  | Dependent Mobile Remark 3 |
| 52 | `ZZDEP_FAX_CNTY1` | CHAR | 3 |  | Dependent fax country 1 |
| 53 | `ZZDEP_FAX_CNTY2` | CHAR | 3 |  | Dependent fax country 2 |
| 54 | `ZZDEP_FAX_CNTY3` | CHAR | 3 |  | Dependent fax country 3 |
| 55 | `ZZDEP_FAX_1` | CHAR | 30 |  | Dependent fax 1 |
| 56 | `ZZDEP_FAX_2` | CHAR | 30 |  | Dependent fax 2 |
| 57 | `ZZDEP_FAX_3` | CHAR | 30 |  | Dependent fax 3 |
| 58 | `ZZDEP_FAX_EXT1` | CHAR | 10 |  | Dependent fax extension 1 |
| 59 | `ZZDEP_FAX_EXT2` | CHAR | 10 |  | Dependent fax extension 2 |
| 60 | `ZZDEP_FAX_EXT3` | CHAR | 10 |  | Dependent fax extension 3 |
| 61 | `ZZDEP_FAX_NOT1` | CHAR | 1 |  | Flag: Dependent Fax Not Used 1 |
| 62 | `ZZDEP_FAX_NOT2` | CHAR | 1 |  | Flag: Dependent Fax Not Used 2 |
| 63 | `ZZDEP_FAX_NOT3` | CHAR | 1 |  | Flag: Dependent Fax Not Used 3 |
| 64 | `ZZDEP_FAX_RMK1` | CHAR | 50 |  | Dependent Fax Remark 1 |
| 65 | `ZZDEP_FAX_RMK2` | CHAR | 50 |  | Dependent Fax Remark 2 |
| 66 | `ZZDEP_FAX_RMK3` | CHAR | 50 |  | Dependent Fax Remark 3 |
| 67 | `ZZDEP_EMAIL_1` | CHAR | 241 |  | Dependent email address 1 |
| 68 | `ZZDEP_EMAIL_2` | CHAR | 241 |  | Dependent email address 2 |
| 69 | `ZZDEP_EMAIL_3` | CHAR | 241 |  | Dependent email address 3 |
| 70 | `ZZDEP_EMAIL_NOT1` | CHAR | 1 |  | Flag: Dependent Email Not Used 1 |
| 71 | `ZZDEP_EMAIL_NOT2` | CHAR | 1 |  | Flag: Dependent Email Not Used 2 |
| 72 | `ZZDEP_EMAIL_NOT3` | CHAR | 1 |  | Flag: Dependent Email Not Used 3 |
| 73 | `ZZDEP_EMAIL_RMK1` | CHAR | 50 |  | Dependent Email Remark 1 |
| 74 | `ZZDEP_EMAIL_RMK2` | CHAR | 50 |  | Dependent Email Remark 2 |
| 75 | `ZZDEP_EMAIL_RMK3` | CHAR | 50 |  | Dependent Email Remark 3 |
| 76 | `ZZDEP_DEFLT_COMM` | CHAR | 3 |  | Dependent communication method |

# ZISCS_PROGR_ID
**Description:** Programme ID Record
**Total Fields:** 16
**Key Fields:** MANDT, PROG_ID

## Programs Using This Table
- `ziscs0800`
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscs0808`
- `ziscs0810`
- `ziscs0810a`
- `ziscs0832`
- `ziscs1031`
- `ziscs1033`
- `ziscs1116`
- `ziscs_email_trig`
- `ziscspc_eec_action_badges`
- `ziscspc_ngo_myprofile_hq======ft`
- `ziscspc_ngo_myprofile_hq_sdu==ft`
- `ziscspc_ngo_search_hq=========ft`
- `ziscspc_ngo_search_hq_sdu=====ft`
- `zisfi0305`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `PROG_DESC` | CHAR | 30 |  | Programme Description |
| 4 | `VALID_FROM` | DATS | 8 |  | Programme Valid From |
| 5 | `VALID_UPTO` | DATS | 8 |  | Programme Valid Upto |
| 6 | `NGO_EDIT_LOCK_DATE` | DATS | 8 |  | NGO Edit Lock Date |
| 7 | `QUOTA` | CHAR | 10 |  | Quota |
| 8 | `QUOTA_HIDE` | CHAR | 1 |  | Quota Hide |
| 9 | `NGO_MASK` | CHAR | 1 |  | NGO Mask |
| 10 | `PROG` | CHAR | 3 |  | Programme type |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `ERZET` | TIMS | 6 |  | Entry time |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 16 | `AEZET` | TIMS | 6 |  | Time last change was made |

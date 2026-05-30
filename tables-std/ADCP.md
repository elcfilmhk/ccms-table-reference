# `ADCP`

**Description:** Address Communication — communication preferences
**Category:** Standard SAP Table
**References:** 24 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/adcp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 35 fields | **Data types:** CHAR(33), DATS(1), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DATE_TO` | AD_DATE_TO | — | DATS | 8 | 0 | Valid-to date in current Release only 99991231 possible |
| `COMP_PERS` | AD_CMP_PRS | — | CHAR | 1 | 0 | Flag: Person in company (C) or private (P) address |
| `SO_KEY` | AD_SO_KEY | — | CHAR | 10 | 0 | SAP-Office key |
| `DEPARTMENT` | AD_DPRTMNT | — | CHAR | 40 | 0 | Department |
| `FUNCTION` | AD_FNCTN | — | CHAR | 40 | 0 | Function |
| `BUILDING` | AD_BLDNG_P | — | CHAR | 10 | 0 | Building (number or code) |
| `FLOOR` | AD_FLOOR | — | CHAR | 10 | 0 | Floor in building |
| `ROOMNUMBER` | AD_ROOMNUM | — | CHAR | 10 | 0 | Room or Appartment Number |
| `ID_CODE` | AD_ID_CODE | — | CHAR | 10 | 0 | Short name for correspondence |
| `IH_MAIL` | AD_IH_MAIL | — | CHAR | 10 | 0 | Int. mail postal code |
| `SORT1` | AD_SORTOLD | — | CHAR | 20 | 0 | (Not Supported) Search Term |
| `SORT2` | AD_SORTOLD | — | CHAR | 20 | 0 | (Not Supported) Search Term |
| `SORT_PHN` | AD_SRTPHN | — | CHAR | 20 | 0 | (Not Supported) Phonetic Search Sort Field |
| `ALT_COMPNY` | AD_ALTCMPY | ADRC | CHAR | 10 | 0 | Business address number, if different (not used) |
| `DEFLT_COMM` | AD_COMM | TSAC | CHAR | 3 | 0 | Communication Method (Key) (Business Address Services) |
| `TEL_NUMBER` | AD_TLNMBR1 | — | CHAR | 30 | 0 | First telephone no.: dialling code+number |
| `TEL_EXTENS` | AD_TLXTNS1 | — | CHAR | 10 | 0 | First Telephone No.: Extension |
| `FAX_NUMBER` | AD_FXNMBR1 | — | CHAR | 30 | 0 | First fax no.: dialling code+number |
| `FAX_EXTENS` | AD_FXXTNS1 | — | CHAR | 10 | 0 | First fax no.: extension |
| `FLAGCOMM2` | AD_FLGCM02 | — | CHAR | 1 | 0 | Flag: Telephone number(s) maintained |
| `FLAGCOMM3` | AD_FLGCM03 | — | CHAR | 1 | 0 | Flag: Fax number(s) maintained |
| `FLAGCOMM4` | AD_FLGCM04 | — | CHAR | 1 | 0 | Flag: Teletex number(s) maintained |
| `FLAGCOMM5` | AD_FLGCM05 | — | CHAR | 1 | 0 | Flag: Telex number(s) maintained |
| `FLAGCOMM6` | AD_FLGCM06 | — | CHAR | 1 | 0 | Indicator: E-Mail Address(es) Maintained |
| `FLAGCOMM7` | AD_FLGCM07 | — | CHAR | 1 | 0 | Flag: RML (remote mail) addresse(s) maintained |
| `FLAGCOMM8` | AD_FLGCM08 | — | CHAR | 1 | 0 | Flag: X.400 addresse(s) maintained |
| `FLAGCOMM9` | AD_FLGCM09 | — | CHAR | 1 | 0 | Flag: RFC destination(s) maintained |
| `FLAGCOMM10` | AD_FLGCM10 | — | CHAR | 1 | 0 | Flag: Printer maintained |
| `FLAGCOMM11` | AD_FLGCM11 | — | CHAR | 1 | 0 | Flag: SSF maintained |
| `FLAGCOMM12` | AD_FLGCM12 | — | CHAR | 1 | 0 | Flag: URI/FTP address maintained |
| `FLAGCOMM13` | AD_FLGCM13 | — | CHAR | 1 | 0 | Flag: Pager address maintained |
| `ADCP_UUID` | AD_UUID | — | RAW | 16 | 0 | UUID Used in the Address |
| `UUID_BELATED` | AD_UUID_BELATED | — | CHAR | 1 | 0 | Indicator: UUID was generated later |
| `ID_CATEGORY` | AD_ID_CATEGORY | — | CHAR | 1 | 0 | Category of an Address ID |
| `ADCP_ERR_STATUS` | AD_ERR_STATUS | — | CHAR | 1 | 0 | Error Status of Address |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDRNUMBER` | ADCP | CLIENT | ADRC |  | |
| `ADDRNUMBER` | ADCP | ADDRNUMBER | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `ADDRNUMBER` | ADCP | NATION | ADRC |  | |
| `ALT_COMPNY` | * |  | ADRC |  | |
| `ALT_COMPNY` | * |  | ADRC |  | |
| `ALT_COMPNY` | ADCP | CLIENT | ADRC |  | |
| `ALT_COMPNY` | ADCP | ALT_COMPNY | ADRC |  | |
| `CLIENT` | ADCP | CLIENT | T000 |  | |
| `DEFLT_COMM` | ADCP | DEFLT_COMM | TSAC |  | |
| `NATION` | ADCP | NATION | TSADV |  | |
| `PERSNUMBER` | ADCP | NATION | ADRP |  | |
| `PERSNUMBER` | ADCP | CLIENT | ADRP |  | |
| `PERSNUMBER` | ADCP | PERSNUMBER | ADRP |  | |
| `PERSNUMBER` | * |  | ADRP |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
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
- `ziscs0467.txt`
- `ziscv06a.txt`
- `zisdm0017.txt`
- `zisdm0091.txt`
- `zisfi0131.txt`
- `zisfi0146.txt`
- `zisfi0148f01.txt`
- `zisfi0156.txt`
- `zmmpre030s.txt`
- `zmmprsi01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
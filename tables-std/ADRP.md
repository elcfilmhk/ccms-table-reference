# `ADRP`

**Description:** Address Person — person master data
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 8 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/adrp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 39 fields | **Data types:** CHAR(35), DATS(1), LANG(2), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DATE_TO` | AD_DATE_TO | — | DATS | 8 | 0 | Valid-to date in current Release only 99991231 possible |
| `TITLE` | AD_TITLE | TSAD3 | CHAR | 4 | 0 | Form-of-Address Key |
| `NAME_FIRST` | AD_NAMEFIR | — | CHAR | 40 | 0 | First name |
| `NAME_LAST` | AD_NAMELAS | — | CHAR | 40 | 0 | Last name |
| `NAME2` | AD_NAME2_P | — | CHAR | 40 | 0 | Name of person at birth |
| `NAMEMIDDLE` | AD_NAMEMID | — | CHAR | 40 | 0 | Middle name or second forename of a person |
| `NAME_LAST2` | AD_NAMLAS2 | — | CHAR | 40 | 0 | Second surname of a person |
| `NAME_TEXT` | AD_NAMTEXT | — | CHAR | 80 | 0 | Full Name of Person |
| `CONVERTED` | AD_NAMCONV | — | CHAR | 1 | 0 | Status of Field &#039;Full Name&#039; NAME_TEXT |
| `TITLE_ACA1` | AD_TITLE1 | TSAD2 | CHAR | 4 | 0 | Academic Title: Key |
| `TITLE_ACA2` | AD_TITLE2 | TSAD2 | CHAR | 4 | 0 | Second academic title (key) |
| `PREFIX1` | AD_PREFIX | TSAD4 | CHAR | 4 | 0 | Name Prefix (Key) |
| `PREFIX2` | AD_PREFIX2 | TSAD4 | CHAR | 4 | 0 | 2nd name prefix (key) |
| `TITLE_SPPL` | AD_TITLES | TSAD5 | CHAR | 4 | 0 | Name supplement, e.g. noble title (key) |
| `NICKNAME` | AD_NICKNAM | — | CHAR | 40 | 0 | Nickname or name used |
| `INITIALS` | AD_INITS | — | CHAR | 10 | 0 | &quot;Middle Initial&quot; or personal initials |
| `NAMEFORMAT` | AD_FORMAT | T005N | CHAR | 2 | 0 | Name format |
| `NAMCOUNTRY` | AD_NAMCTRY | T005 | CHAR | 3 | 0 | Country for name format rule |
| `PROFESSION` | AD_PROFESS | — | CHAR | 40 | 0 | Profession |
| `SEX` | AD_SEX | — | CHAR | 1 | 0 | Gender key |
| `LANGU` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `PERS_GROUP` | AD_GROUP_P | TSAD8 | CHAR | 4 | 0 | Person Group (Key) (Business Address Services) |
| `FLAGGROUPS` | AD_FLGGP_P | — | CHAR | 1 | 0 | Flag: There are other person group assignments |
| `SORT1` | AD_SORT1 | — | CHAR | 20 | 0 | Search Term 1 |
| `SORT2` | AD_SORT2 | — | CHAR | 20 | 0 | Search Term 2 |
| `SORT_PHN` | AD_SRTPHN | — | CHAR | 20 | 0 | (Not Supported) Phonetic Search Sort Field |
| `ADDR_COMP` | AD_ADDRCOM | — | CHAR | 10 | 0 | (not used) |
| `ADDR_PERS` | AD_ADDRPER | — | CHAR | 10 | 0 | (not used) |
| `FLPERSTEL` | AD_FLPTEL | — | CHAR | 1 | 0 | Flag: person has personal telephone numbers |
| `FLPERSCOMM` | AD_FLPCOMM | — | CHAR | 1 | 0 | Flag: Person has personal comm. numbers (apart from Tel.) |
| `PERSORIGIN` | AD_ORIGINP | TSAD6 | CHAR | 4 | 0 | Personal data source (key) |
| `MC_NAMEFIR` | AD_MC_NMFI | — | CHAR | 25 | 0 | First name in upper case for search help |
| `MC_NAMELAS` | AD_MC_NMLA | — | CHAR | 25 | 0 | Last name in upper-case for search help |
| `MC_NAME2` | AD_MC_NAM2 | — | CHAR | 25 | 0 | NAME2 field in upper case for matchcode |
| `LANGU_CREA` | AD_LANGUCR | — | LANG | 1 | 0 | Address record creation original language |
| `ADRP_UUID` | AD_UUID | — | RAW | 16 | 0 | UUID Used in the Address |
| `UUID_BELATED` | AD_UUID_BELATED | — | CHAR | 1 | 0 | Indicator: UUID was generated later |
| `ID_CATEGORY` | AD_ID_CATEGORY | — | CHAR | 1 | 0 | Category of an Address ID |
| `ADRP_ERR_STATUS` | AD_ERR_STATUS | — | CHAR | 1 | 0 | Error Status of Address |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CLIENT` | ADRP | CLIENT | T000 |  | |
| `LANGU` | ADRP | LANGU | T002 |  | |
| `NAMCOUNTRY` | ADRP | CLIENT | T005 |  | |
| `NAMCOUNTRY` | ADRP | NAMCOUNTRY | T005 |  | |
| `NAMEFORMAT` | ADRP | NAMEFORMAT | T005N |  | |
| `NAMEFORMAT` | ADRP | CLIENT | T005N |  | |
| `NAMEFORMAT` | ADRP | NAMCOUNTRY | T005N |  | |
| `NATION` | ADRP | NATION | TSADV |  | |
| `PERSORIGIN` | ADRP | CLIENT | TSAD6 |  | |
| `PERSORIGIN` | ADRP | PERSORIGIN | TSAD6 |  | |
| `PERS_GROUP` | ADRP | PERS_GROUP | TSAD8 |  | |
| `PREFIX1` | ADRP | CLIENT | TSAD4 |  | |
| `PREFIX1` | ADRP | PREFIX1 | TSAD4 |  | |
| `PREFIX2` | ADRP | PREFIX2 | TSAD4 |  | |
| `PREFIX2` | ADRP | CLIENT | TSAD4 |  | |
| `TITLE` | ADRP | CLIENT | TSAD3 |  | |
| `TITLE` | ADRP | TITLE | TSAD3 |  | |
| `TITLE_ACA1` | ADRP | CLIENT | TSAD2 |  | |
| `TITLE_ACA1` | ADRP | TITLE_ACA1 | TSAD2 |  | |
| `TITLE_ACA2` | ADRP | CLIENT | TSAD2 |  | |
| `TITLE_ACA2` | ADRP | TITLE_ACA2 | TSAD2 |  | |
| `TITLE_SPPL` | ADRP | CLIENT | TSAD5 |  | |
| `TITLE_SPPL` | ADRP | TITLE_SPPL | TSAD5 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `name_text`, `persnumber`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_ossnote_445575.txt`
- `ziscv08_f01.txt`
- `ziscv08nv_f01.txt`
- `ziscv08nv_test_f01.txt`
- `zisdm0239f01.txt`
- `zissd00089_f01.txt`
- `zmmpre030s.txt`
- `zmmprsi01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
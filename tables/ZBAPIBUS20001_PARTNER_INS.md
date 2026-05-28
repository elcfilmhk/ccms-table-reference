# ZBAPIBUS20001_PARTNER_INS
**Description:** BO BusProcessND: Process Partner for a Transaction Create()
**Total Fields:** 101
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0111`
- `ziscs0118`
- `ziscs0119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `REF_GUID` | CHAR | 32 |  | Globally Unique Identifier in 32-Character Display |
| 2 | `REF_HANDLE` | NUMC | 10 |  | Handle |
| 3 | `REF_KIND` | CHAR | 1 |  | Object Type |
| 4 | `REF_PARTNER_HANDLE` | NUMC | 4 |  | Count parameters |
| 5 | `REF_PARTNER_FCT` | CHAR | 8 |  | Partner Function |
| 6 | `REF_PARTNER_NO` | CHAR | 16 |  | Partner Number for Use Outside Partner Processing |
| 7 | `REF_NO_TYPE` | CHAR | 2 |  | Type of Partner No. (GUID, pers. no., for example), internal |
| 8 | `REF_DISPLAY_TYPE` | CHAR | 2 |  | Object Type for which Partner Number is to be Shown |
| 9 | `PARTNER_FCT` | CHAR | 8 |  | Partner Function |
| 10 | `PARTNER_NO` | CHAR | 32 |  | Partner Number |
| 11 | `NO_TYPE` | CHAR | 2 |  | Type of Partner No. (GUID, pers. no., for example), internal |
| 12 | `DISPLAY_TYPE` | CHAR | 2 |  | Object Type for which Partner Number is to be Shown |
| 13 | `KIND_OF_ENTRY` | CHAR | 1 |  | Source of a partner in a transaction |
| 14 | `MAINPARTNER` | CHAR | 1 |  | Main Partner (For Ambiguous Partner Functions) |
| 15 | `RELATION_PARTNER` | CHAR | 32 |  | Globally Unique Identifier in 32-Character Display |
| 16 | `BUSINESSPARTNERGUID` | CHAR | 32 |  | GUID of a Business Partner in CHAR 32 Format for BAPIs |
| 17 | `ADDRESS_GUID` | CHAR | 32 |  | GUID for an Address Object in BAPI Format |
| 18 | `ADDR_NR` | CHAR | 10 |  | Address number |
| 19 | `ADDR_NP` | CHAR | 10 |  | Person number |
| 20 | `ADDR_TYPE` | CHAR | 1 |  | Address type (1=Organization, 2=Person, 3=Contact person) |
| 21 | `ADDR_ORIGIN` | CHAR | 1 |  | Origin of a Partner Address |
| 22 | `STD_BP_ADDRESS` | CHAR | 1 |  | Standard Business Partner Address(Dependent On Address Type) |
| 23 | `ADDR_OPERATION` | CHAR | 6 |  | Business Transaction for BP Address Determination |
| 24 | `CALENDAR` | CHAR | 1 |  | Maintain Calendar for the Partner? |
| 25 | `DISABLED` | CHAR | 1 |  | No INBOX Selection for the Partner |
| 26 | `TITLE_P` | CHAR | 30 |  | Title text |
| 27 | `FIRSTNAME` | CHAR | 40 |  | First name |
| 28 | `LASTNAME` | CHAR | 40 |  | Last name |
| 29 | `BIRTH_NAME` | CHAR | 40 |  | Name of person at birth |
| 30 | `MIDDLENAME` | CHAR | 40 |  | Middle name or second forename of a person |
| 31 | `SECONDNAME` | CHAR | 40 |  | Second surname of a person |
| 32 | `FULLNAME` | CHAR | 80 |  | Complete personal name |
| 33 | `FULLNAME_X` | CHAR | 1 |  | NAME_TEXT field status |
| 34 | `TITLE_ACA1` | CHAR | 20 |  | Academic Title: Written Form |
| 35 | `TITLE_ACA2` | CHAR | 20 |  | Academic Title: Written Form |
| 36 | `PREFIX1` | CHAR | 20 |  | Name prefix |
| 37 | `PREFIX2` | CHAR | 20 |  | Name prefix |
| 38 | `TITLE_SPPL` | CHAR | 20 |  | Name supplement, e.g. noble title (written form) |
| 39 | `NICKNAME` | CHAR | 40 |  | Nickname or name used |
| 40 | `INITIALS` | CHAR | 10 |  | "Middle Initial" or personal initials |
| 41 | `NAMEFORMAT` | CHAR | 2 |  | Name format |
| 42 | `NAMCOUNTRY` | CHAR | 3 |  | Country for name format rule |
| 43 | `LANGU_P` | LANG | 1 |  | Language Key |
| 44 | `LANGUP_ISO` | CHAR | 2 |  | Language according to ISO 639 |
| 45 | `SORT1_P` | CHAR | 20 |  | Search term 1 |
| 46 | `SORT2_P` | CHAR | 20 |  | Search term 2 |
| 47 | `DEPARTMENT` | CHAR | 40 |  | Department |
| 48 | `FUNCTION` | CHAR | 40 |  | Function |
| 49 | `BUILDING_P` | CHAR | 10 |  | Building (number or code) |
| 50 | `FLOOR_P` | CHAR | 10 |  | Floor in building |
| 51 | `ROOM_NO_P` | CHAR | 10 |  | Room or Appartment Number |
| 52 | `INITS_SIG` | CHAR | 10 |  | Short name for correspondence |
| 53 | `INHOUSE_ML` | CHAR | 10 |  | Int. mail postal code |
| 54 | `COMM_TYPE` | CHAR | 3 |  | Communication Method (Key) (Business Address Services) |
| 55 | `TITLE` | CHAR | 30 |  | Title text |
| 56 | `NAME` | CHAR | 40 |  | Name 1 |
| 57 | `NAME_2` | CHAR | 40 |  | Name 2 |
| 58 | `NAME_3` | CHAR | 40 |  | Name 3 |
| 59 | `NAME_4` | CHAR | 40 |  | Name 4 |
| 60 | `C_O_NAME` | CHAR | 40 |  | c/o name |
| 61 | `CITY` | CHAR | 40 |  | City |
| 62 | `DISTRICT` | CHAR | 40 |  | District |
| 63 | `CITY_NO` | CHAR | 12 |  | City code for city/street file |
| 64 | `DISTRCT_NO` | CHAR | 8 |  | District code for City and Street file |
| 65 | `CHCKSTATUS` | CHAR | 1 |  | City file test status |
| 66 | `POSTL_COD1` | CHAR | 10 |  | City postal code |
| 67 | `POSTL_COD2` | CHAR | 10 |  | PO Box postal code |
| 68 | `POSTL_COD3` | CHAR | 10 |  | Company postal code (for large customers) |
| 69 | `PO_BOX` | CHAR | 10 |  | PO Box |
| 70 | `PO_BOX_CIT` | CHAR | 40 |  | PO Box city |
| 71 | `PBOXCIT_NO` | CHAR | 12 |  | City PO box code (City file) |
| 72 | `DELIV_DIS` | CHAR | 15 |  | Post delivery district |
| 73 | `TRANSPZONE` | CHAR | 10 |  | Transportation zone to or from which the goods are delivered |
| 74 | `STREET` | CHAR | 60 |  | Street |
| 75 | `STREET_NO` | CHAR | 12 |  | Street code for city/street file |
| 76 | `STR_ABBR` | CHAR | 2 |  | Abbreviation of street name (e.g in Spain) |
| 77 | `HOUSE_NO` | CHAR | 10 |  | House Number |
| 78 | `HOUSE_NO2` | CHAR | 10 |  | House number supplement |
| 79 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 80 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 81 | `STR_SUPPL3` | CHAR | 40 |  | Street 4 |
| 82 | `LOCATION` | CHAR | 40 |  | Street 5 |
| 83 | `BUILDING` | CHAR | 10 |  | old: building (no. or abbreviation) |
| 84 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 85 | `ROOM_NO` | CHAR | 10 |  | Room or Appartment Number |
| 86 | `COUNTRY` | CHAR | 3 |  | Country Indic. |
| 87 | `COUNTRYISO` | CHAR | 2 |  | Country ISO code |
| 88 | `LANGU` | LANG | 1 |  | Language Key |
| 89 | `LANGU_ISO` | CHAR | 2 |  | Language according to ISO 639 |
| 90 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 91 | `SORT1` | CHAR | 20 |  | Search term 1 |
| 92 | `SORT2` | CHAR | 20 |  | Search term 2 |
| 93 | `TIME_ZONE` | CHAR | 6 |  | Address time zone |
| 94 | `TAXJURCODE` | CHAR | 15 |  | Tax jurisdiction code |
| 95 | `ADR_NOTES` | CHAR | 50 |  | Address notes |
| 96 | `TEL1_NUMBR` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 97 | `TEL1_EXT` | CHAR | 10 |  | First Telephone No.: Extension |
| 98 | `FAX_NUMBER` | CHAR | 30 |  | First fax no.: dialling code+number |
| 99 | `FAX_EXTENS` | CHAR | 10 |  | First fax no.: extension |
| 100 | `E_MAIL` | CHAR | 241 |  | E-Mail Address |
| 101 | `BUILD_LONG` | CHAR | 20 |  | Building (number or code) |

# `ADRC`

**Description:** Address — address master data
**Category:** Standard SAP Table
**References:** 276 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/adrc/) — validated 2026-05-30, schema v1.0
**Schema fields:** 94 fields | **Data types:** CHAR(90), DATS(1), LANG(2), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DATE_TO` | AD_DATE_TO | — | DATS | 8 | 0 | Valid-to date in current Release only 99991231 possible |
| `TITLE` | AD_TITLE | TSAD3 | CHAR | 4 | 0 | Form-of-Address Key |
| `NAME1` | AD_NAME1 | — | CHAR | 40 | 0 | Name 1 |
| `NAME2` | AD_NAME2 | — | CHAR | 40 | 0 | Name 2 |
| `NAME3` | AD_NAME3 | — | CHAR | 40 | 0 | Name 3 |
| `NAME4` | AD_NAME4 | — | CHAR | 40 | 0 | Name 4 |
| `NAME_TEXT` | AD_NAMETXT | — | CHAR | 50 | 0 | Converted name field (with form of address) |
| `NAME_CO` | AD_NAME_CO | — | CHAR | 40 | 0 | c/o name |
| `CITY1` | AD_CITY1 | — | CHAR | 40 | 0 | City |
| `CITY2` | AD_CITY2 | — | CHAR | 40 | 0 | District |
| `CITY_CODE` | AD_CITYNUM | ADRCITY | CHAR | 12 | 0 | City code for city/street file |
| `CITYP_CODE` | AD_CITYPNM | ADRCITYPRT | CHAR | 8 | 0 | District code for City and Street file |
| `HOME_CITY` | AD_CITY3 | — | CHAR | 40 | 0 | City (different from postal city) |
| `CITYH_CODE` | AD_CITYHNM | ADRCITY | CHAR | 12 | 0 | Different city for city/street file |
| `CHCKSTATUS` | AD_CHECKST | — | CHAR | 1 | 0 | City file test status |
| `REGIOGROUP` | REGIOGROUP | ADRREGGRP | CHAR | 8 | 0 | Regional structure grouping |
| `POST_CODE1` | AD_PSTCD1 | — | CHAR | 10 | 0 | City postal code |
| `POST_CODE2` | AD_PSTCD2 | — | CHAR | 10 | 0 | PO Box Postal Code |
| `POST_CODE3` | AD_PSTCD3 | — | CHAR | 10 | 0 | Company Postal Code (for Large Customers) |
| `PCODE1_EXT` | AD_PST1XT | — | CHAR | 10 | 0 | (Not Supported)City Postal Code Extension, e.g. ZIP+4+2 Code |
| `PCODE2_EXT` | AD_PST2XT | — | CHAR | 10 | 0 | (Not Supported) PO Box Postal Code Extension |
| `PCODE3_EXT` | AD_PST3XT | — | CHAR | 10 | 0 | (Not Supported) Major Customer Postal Code Extension |
| `PO_BOX` | AD_POBX | — | CHAR | 10 | 0 | PO Box |
| `DONT_USE_P` | AD_NO_USEP | TSAD12 | CHAR | 4 | 0 | PO Box Address Undeliverable Flag |
| `PO_BOX_NUM` | AD_POBXNUM | — | CHAR | 1 | 0 | Flag: PO Box Without Number |
| `PO_BOX_LOC` | AD_POBXLOC | — | CHAR | 40 | 0 | PO Box city |
| `CITY_CODE2` | AD_CIT2NUM | ADRCITY | CHAR | 12 | 0 | City PO box code (City file) |
| `PO_BOX_REG` | AD_POBXREG | T005S | CHAR | 3 | 0 | Region for PO Box (Country, State, Province, ...) |
| `PO_BOX_CTY` | AD_POBXCTY | T005 | CHAR | 3 | 0 | PO box country |
| `POSTALAREA` | AD_PSTLAR | — | CHAR | 15 | 0 | (Not Supported) Post Delivery District |
| `TRANSPZONE` | LZONE | TZONE | CHAR | 10 | 0 | Transportation zone to or from which the goods are delivered |
| `STREET` | AD_STREET | — | CHAR | 60 | 0 | Street |
| `DONT_USE_S` | AD_NO_USES | TSAD12 | CHAR | 4 | 0 | Street Address Undeliverable Flag |
| `STREETCODE` | AD_STRNUM | ADRSTREET | CHAR | 12 | 0 | Street Number for City/Street File |
| `STREETABBR` | AD_STRABBR | ADRSTRTYPE | CHAR | 2 | 0 | (Not Supported) Abbreviation of Street Name |
| `HOUSE_NUM1` | AD_HSNM1 | — | CHAR | 10 | 0 | House Number |
| `HOUSE_NUM2` | AD_HSNM2 | — | CHAR | 10 | 0 | House number supplement |
| `HOUSE_NUM3` | AD_HSNM3 | — | CHAR | 10 | 0 | (Not supported) House Number Range |
| `STR_SUPPL1` | AD_STRSPP1 | — | CHAR | 40 | 0 | Street 2 |
| `STR_SUPPL2` | AD_STRSPP2 | — | CHAR | 40 | 0 | Street 3 |
| `STR_SUPPL3` | AD_STRSPP3 | — | CHAR | 40 | 0 | Street 4 |
| `LOCATION` | AD_LCTN | — | CHAR | 40 | 0 | Street 5 |
| `BUILDING` | AD_BLDNG | — | CHAR | 20 | 0 | Building (Number or Code) |
| `FLOOR` | AD_FLOOR | — | CHAR | 10 | 0 | Floor in building |
| `ROOMNUMBER` | AD_ROOMNUM | — | CHAR | 10 | 0 | Room or Appartment Number |
| `COUNTRY` | LAND1 | T005 | CHAR | 3 | 0 | Country Key |
| `LANGU` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `REGION` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `ADDR_GROUP` | AD_GROUP | TSAD7 | CHAR | 4 | 0 | Address Group (Key) (Business Address Services) |
| `FLAGGROUPS` | AD_FLGGP | — | CHAR | 1 | 0 | Flag: There are more address group assignments |
| `PERS_ADDR` | AD_PRSADDR | — | CHAR | 1 | 0 | Flag: This is a personal address |
| `SORT1` | AD_SORT1 | — | CHAR | 20 | 0 | Search Term 1 |
| `SORT2` | AD_SORT2 | — | CHAR | 20 | 0 | Search Term 2 |
| `SORT_PHN` | AD_SRTPHN | — | CHAR | 20 | 0 | (Not Supported) Phonetic Search Sort Field |
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
| `ADDRORIGIN` | AD_ORIGINA | TSAD6 | CHAR | 4 | 0 | (Not Supported) Address Data Source (Key) |
| `MC_NAME1` | AD_MC_NAME | — | CHAR | 25 | 0 | Name (field NAME1) in upper case for matchcode |
| `MC_CITY1` | AD_MC_CITY | — | CHAR | 25 | 0 | City name in upper case for search help |
| `MC_STREET` | AD_MC_STRT | — | CHAR | 25 | 0 | Street name in upper case for search help |
| `EXTENSION1` | AD_EXTENS1 | — | CHAR | 40 | 0 | Extension (only for data conversion) (e.g. data line) |
| `EXTENSION2` | AD_EXTENS2 | — | CHAR | 40 | 0 | Extension (only for data conversion) (e.g. telebox) |
| `TIME_ZONE` | AD_TZONE | TTZZ | CHAR | 6 | 0 | Address time zone |
| `TAXJURCODE` | AD_TXJCD | — | CHAR | 15 | 0 | Tax Jurisdiction |
| `ADDRESS_ID` | AD_ADDR_ID | — | CHAR | 10 | 0 | (Not supported) Physical address ID |
| `LANGU_CREA` | AD_LANGUCR | — | LANG | 1 | 0 | Address record creation original language |
| `ADRC_UUID` | AD_UUID | — | RAW | 16 | 0 | UUID Used in the Address |
| `UUID_BELATED` | AD_UUID_BELATED | — | CHAR | 1 | 0 | Indicator: UUID was generated later |
| `ID_CATEGORY` | AD_ID_CATEGORY | — | CHAR | 1 | 0 | Category of an Address ID |
| `ADRC_ERR_STATUS` | AD_ERR_STATUS | — | CHAR | 1 | 0 | Error Status of Address |
| `PO_BOX_LOBBY` | AD_PO_BOX_LBY | — | CHAR | 40 | 0 | PO Box Lobby |
| `DELI_SERV_TYPE` | AD_DELIVERY_SERVICE_TYPE | ADDRC_DELI_SERV | CHAR | 4 | 0 | Type of Delivery Service |
| `DELI_SERV_NUMBER` | AD_DELIVERY_SERVICE_NUMBER | — | CHAR | 10 | 0 | Number of Delivery Service |
| `COUNTY_CODE` | AD_CNTYNUM | — | CHAR | 8 | 0 | County code for county |
| `COUNTY` | AD_COUNTY | — | CHAR | 40 | 0 | County |
| `TOWNSHIP_CODE` | AD_TWSHPNUM | — | CHAR | 8 | 0 | Township code for Township |
| `TOWNSHIP` | AD_TOWNSHIP | — | CHAR | 40 | 0 | Township |
| `MC_COUNTY` | AD_MC_COUNTY | — | CHAR | 25 | 0 | County name in upper case for search help |
| `MC_TOWNSHIP` | AD_MC_TWSHP | — | CHAR | 25 | 0 | Township name in upper case for search help |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDRORIGIN` | ADRC | ADDRORIGIN | TSAD6 |  | |
| `ADDRORIGIN` | ADRC | CLIENT | TSAD6 |  | |
| `ADDR_GROUP` | ADRC | ADDR_GROUP | TSAD7 |  | |
| `CITYH_CODE` | ADRC | CLIENT | ADRCITY |  | |
| `CITYH_CODE` | ADRC | COUNTRY | ADRCITY |  | |
| `CITYH_CODE` | ADRC | CITYH_CODE | ADRCITY |  | |
| `CITYP_CODE` | ADRC | CLIENT | ADRCITYPRT |  | |
| `CITYP_CODE` | ADRC | COUNTRY | ADRCITYPRT |  | |
| `CITYP_CODE` | ADRC | CITY_CODE | ADRCITYPRT |  | |
| `CITYP_CODE` | ADRC | CITYP_CODE | ADRCITYPRT |  | |
| `CITY_CODE` | ADRC | COUNTRY | ADRCITY |  | |
| `CITY_CODE` | ADRC | CITY_CODE | ADRCITY |  | |
| `CITY_CODE` | ADRC | CLIENT | ADRCITY |  | |
| `CITY_CODE2` | ADRC | CLIENT | ADRCITY |  | |
| `CITY_CODE2` | * |  | ADRCITY |  | |
| `CITY_CODE2` | ADRC | CITY_CODE2 | ADRCITY |  | |
| `CLIENT` | ADRC | CLIENT | T000 |  | |
| `COUNTRY` | ADRC | CLIENT | T005 |  | |
| `COUNTRY` | ADRC | COUNTRY | T005 |  | |
| `DEFLT_COMM` | ADRC | DEFLT_COMM | TSAC |  | |
| `DELI_SERV_TYPE` | ADRC | CLIENT | ADDRC_DELI_SERV |  | |
| `DELI_SERV_TYPE` | ADRC | DELI_SERV_TYPE | ADDRC_DELI_SERV |  | |
| `DONT_USE_P` | ADRC | CLIENT | TSAD12 |  | |
| `DONT_USE_P` | ADRC | DONT_USE_P | TSAD12 |  | |
| `DONT_USE_S` | ADRC | CLIENT | TSAD12 |  | |
| `DONT_USE_S` | ADRC | DONT_USE_S | TSAD12 |  | |
| `LANGU` | ADRC | LANGU | T002 |  | |
| `NATION` | ADRC | NATION | TSADV |  | |
| `PO_BOX_CTY` | ADRC | CLIENT | T005 |  | |
| `PO_BOX_CTY` | ADRC | PO_BOX_CTY | T005 |  | |
| `PO_BOX_REG` | ADRC | CLIENT | T005S |  | |
| `PO_BOX_REG` | ADRC | PO_BOX_CTY | T005S |  | |
| `PO_BOX_REG` | ADRC | PO_BOX_REG | T005S |  | |
| `REGIOGROUP` | ADRC | REGIOGROUP | ADRREGGRP |  | |
| `REGIOGROUP` | ADRC | CLIENT | ADRREGGRP |  | |
| `REGION` | ADRC | CLIENT | T005S |  | |
| `REGION` | ADRC | COUNTRY | T005S |  | |
| `REGION` | ADRC | REGION | T005S |  | |
| `STREETABBR` | ADRC | STREETABBR | ADRSTRTYPE |  | |
| `STREETABBR` | ADRC | CLIENT | ADRSTRTYPE |  | |
| `STREETABBR` | ADRC | COUNTRY | ADRSTRTYPE |  | |
| `STREETCODE` | ADRC | CLIENT | ADRSTREET |  | |
| `STREETCODE` | ADRC | COUNTRY | ADRSTREET |  | |
| `STREETCODE` | ADRC | STREETCODE | ADRSTREET |  | |
| `TIME_ZONE` | ADRC | CLIENT | TTZZ |  | |
| `TIME_ZONE` | ADRC | TIME_ZONE | TTZZ |  | |
| `TITLE` | ADRC | CLIENT | TSAD3 |  | |
| `TITLE` | ADRC | TITLE | TSAD3 |  | |
| `TRANSPZONE` | ADRC | CLIENT | TZONE |  | |
| `TRANSPZONE` | ADRC | COUNTRY | TZONE |  | |
| `TRANSPZONE` | ADRC | TRANSPZONE | TZONE |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADDRNUMBER`, `CITY2`, `HOUSE_NUM1`, `NATION`, `STREET`, `STR_SUPPL1`, `STR_SUPPL2`, `addrnumber`, `city1`, `city2`, `country`, `date_from`, `date_to`, `floor`, `house_num1`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `nation`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_mo_status.txt`
- `z_get_chin_supply_address_ws.txt`
- `z_get_supply_address_ws.txt`
- `zisbi0011.txt`
- `ziscrm0048.txt`
- `ziscs0031.txt`
- `ziscs0088.txt`
- `ziscs0108.txt`
- `ziscs0150.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- `ziscs0207.txt`
- `ziscs0243.txt`
- `ziscs0525_f01.txt`
- `ziscs0805_f01.txt`
- `ziscsriaufk20.txt`
- `zisdm0135.txt`
- `zisfi0131.txt`
- `zisfi0132.txt`
- `zissd00076.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
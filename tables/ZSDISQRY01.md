# ZSDISQRY01
**Description:** MACS SMIS Query Structure
**Total Fields:** 66
**Key Fields:** _none_

## Programs Using This Table
- `zissd00001`
- `zissd00002`
- `zissd00003`
- `zissd00004`
- `zissd00005`
- `zissd00006`
- `zissd00007`
- `zissd00008`
- `zissd00009`
- `zissd00010`
- `zissd00011`
- `zissd00012`
- `zissd00013`
- `zissd00014`
- `zissd00015`
- `zissd00016`
- `zissd00017`
- `zissd00018`
- `zissd00019`
- `zissd00020`
- `zissd00021`
- `zissd00022`
- `zissd00023`
- `zissd00024`
- `zissd00043`
- `zissd00045`
- `zissd00047`
- `zissd00048`
- `zissd00049`
- `zissd00050`
- `zissd00051`
- `zissd00052`
- `zissd00053`
- `zissd00054`
- `zissd00055`
- `zissd00056`
- `zissd00057`
- `zissd00058`
- `zissd00059`
- `zissd00060`
- `zissd00061`
- `zissd00062`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `VKORG` | CHAR | 4 |  | Sales Organization |
| 3 | `VTWEG` | CHAR | 2 |  | Distribution Channel |
| 4 | `SPART` | CHAR | 2 |  | Division |
| 5 | `VKBUR` | CHAR | 4 |  | Sales Office |
| 6 | `VKGRP` | CHAR | 3 |  | Sales Group |
| 7 | `AUART` | CHAR | 4 |  | Sales Document Type |
| 8 | `FKART` | CHAR | 4 |  | Billing Type |
| 9 | `VBELN` | CHAR | 10 |  | Sales Document |
| 10 | `VBTYP` | CHAR | 1 |  | SD document category |
| 11 | `VBELN_VF` | CHAR | 10 |  | Billing Document |
| 12 | `VBTYP_VF` | CHAR | 1 |  | SD document category |
| 13 | `POSNR` | NUMC | 6 |  | Sales Document Item |
| 14 | `POSNR_VF` | NUMC | 6 |  | Billing item |
| 15 | `UEPOS` | NUMC | 6 |  | Higher-level item in bill of material structures |
| 16 | `KONDA` | CHAR | 2 |  | Price group (customer) |
| 17 | `KDGRP` | CHAR | 2 |  | Customer group |
| 18 | `KONDM` | CHAR | 2 |  | Material Pricing Group |
| 19 | `ZTERM` | CHAR | 4 |  | Terms of Payment Key |
| 20 | `KUNAG` | CHAR | 10 |  | Sold-To Party |
| 21 | `KUNWE` | CHAR | 10 |  | Ship-To Party |
| 22 | `ORT02` | CHAR | 35 |  | District |
| 23 | `AUDAT` | DATS | 8 |  | Document Date (Date Received/Sent) |
| 24 | `FKDAT` | DATS | 8 |  | Billing Date for Billing Index and Printout |
| 25 | `BZIRK` | CHAR | 6 |  | Sales district |
| 26 | `BSTNK` | CHAR | 20 |  | Customer purchase order number |
| 27 | `BSTDK` | DATS | 8 |  | Customer Purchase Order Date |
| 28 | `MATNR` | CHAR | 18 |  | Material Number |
| 29 | `MAKTX` | CHAR | 40 |  | Material Description |
| 30 | `KWMENG` | QUAN | 15 |  | Cumulative Order Quantity in Sales Units |
| 31 | `FKIMG` | QUAN | 13 |  | Actual billed quantity |
| 32 | `VRKME` | UNIT | 3 |  | Sales Unit |
| 33 | `WAERK` | CUKY | 5 |  | SD Document Currency |
| 34 | `NETWR` | CURR | 15 |  | Net Value in Document Currency |
| 35 | `RNETWR` | CURR | 15 |  | Net Value in Document Currency |
| 36 | `WAVWR` | CURR | 13 |  | Cost in document currency |
| 37 | `NETWR_VF` | CURR | 15 |  | Net Value in Document Currency |
| 38 | `WAVWR_VF` | CURR | 13 |  | Cost in document currency |
| 39 | `RNETWR_VF` | CURR | 15 |  | Net Value in Document Currency |
| 40 | `PROVG` | CHAR | 2 |  | Commission group |
| 41 | `CONTRACTC` | QUAN | 10 |  | Contract Consumption |
| 42 | `CONNECTC` | QUAN | 10 |  | Connect Consumption |
| 43 | `UNITC` | UNIT | 3 |  | Unit of Measure |
| 44 | `CONTRACTR` | QUAN | 12 |  | Contract Rating |
| 45 | `CONNECTR` | QUAN | 12 |  | Connect Rating |
| 46 | `UNITR` | UNIT | 3 |  | Unit of Measure |
| 47 | `CONTRACTMTH` | NUMC | 6 |  | Period to analyze - month |
| 48 | `CONNECTMTH` | NUMC | 6 |  | Period to analyze - month |
| 49 | `RETURNMTH` | NUMC | 6 |  | Period to analyze - month |
| 50 | `MTHDIFF` | INT4 | 10 |  | Time Zone |
| 51 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 52 | `HOUSE_NUM2` | CHAR | 10 |  | House number supplement |
| 53 | `STREET` | CHAR | 60 |  | Street |
| 54 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 55 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 56 | `STR_SUPPL3` | CHAR | 40 |  | Street 4 |
| 57 | `LOCATION` | CHAR | 40 |  | Street 5 |
| 58 | `CITY1` | CHAR | 40 |  | City |
| 59 | `HOME_CITY` | CHAR | 40 |  | District |
| 60 | `CITY2` | CHAR | 40 |  | City (different from postal city) |
| 61 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 62 | `POST_CODE1` | CHAR | 10 |  | City postal code |
| 63 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 64 | `TEL_NUMBER` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 65 | `TEL_EXTENS` | CHAR | 10 |  | First Telephone No.: Extension |
| 66 | `BNDDT` | DATS | 8 |  | Date until which bid/quotation is binding (valid-to date) |

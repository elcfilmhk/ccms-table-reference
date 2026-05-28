# ZISFIDUNHI
**Description:** Dunning history table
**Total Fields:** 66
**Key Fields:** MANDT, VKONT, AUSDT, BILL_ID

## Programs Using This Table
- `zisbi0090`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `AUSDT` | DATS | 8 | 🔑 | Date of issue |
| 4 | `BILL_ID` | CHAR | 2 | 🔑 | Bill ID |
| 5 | `TITLE_MEDI` | CHAR | 20 |  | Form of address text |
| 6 | `NAME1` | CHAR | 40 |  | Name 1 |
| 7 | `NAME2` | CHAR | 40 |  | Name 2 |
| 8 | `NAME3` | CHAR | 40 |  | Name 3 |
| 9 | `NAME4` | CHAR | 40 |  | Name 4 |
| 10 | `NAME_ORG1` | CHAR | 40 |  | Name 1 of organization |
| 11 | `NAME_ORG2` | CHAR | 40 |  | Name 2 of organization |
| 12 | `NAME_ORG4` | CHAR | 40 |  | Name 4 of organization |
| 13 | `NAME_CO` | CHAR | 40 |  | c/o name |
| 14 | `VKBEZ` | CHAR | 35 |  | Contract Account Name |
| 15 | `ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 16 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 17 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 18 | `STREET` | CHAR | 60 |  | Street |
| 19 | `HOUSE_NUM2` | CHAR | 10 |  | House number supplement |
| 20 | `BUILDING` | CHAR | 20 |  | Building (Number or Code) |
| 21 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 22 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 23 | `LOCATION` | CHAR | 40 |  | Street 5 |
| 24 | `CITY1` | CHAR | 40 |  | City |
| 25 | `CITY2` | CHAR | 40 |  | District |
| 26 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 27 | `PO_BOX` | CHAR | 10 |  | PO Box |
| 28 | `PO_BOX_LOC` | CHAR | 40 |  | PO Box city |
| 29 | `PO_BOX_CTY` | CHAR | 3 |  | PO box country |
| 30 | `POST_CODE1` | CHAR | 10 |  | City postal code |
| 31 | `POST_CODE2` | CHAR | 10 |  | PO Box Postal Code |
| 32 | `TEL_NUMBER` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 33 | `TEL_EXTENS` | CHAR | 10 |  | First Telephone No.: Extension |
| 34 | `FAX_NUMBER` | CHAR | 30 |  | First fax no.: dialling code+number |
| 35 | `FAX_EXTENS` | CHAR | 10 |  | First fax no.: extension |
| 36 | `CHI_CORR_ADD_IND` | CHAR | 1 |  | BP chinese correspondence indicator |
| 37 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
| 38 | `DUE_VALID_FROM` | DATS | 8 |  | Valid from date for overdue charge |
| 39 | `DUE_VALID_TO` | DATS | 8 |  | Valid to date for overdue charge |
| 40 | `CONSUM_DAYS` | INT4 | 10 |  | number of days of consumption |
| 41 | `DUE_DATE` | DATS | 8 |  | Dunning due date |
| 42 | `TYPE` | CHAR | 1 |  | Business Partner Category |
| 43 | `SENDCONTROL_GP` | CHAR | 4 |  | Dispatch control for original customer |
| 44 | `FLOOR_VBS` | CHAR | 10 |  | Floor in building |
| 45 | `ROOMNUMBER_VBS` | CHAR | 10 |  | Room or Apartment Number |
| 46 | `S_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 47 | `S_STREET` | CHAR | 60 |  | Street |
| 48 | `S_CITY1` | CHAR | 40 |  | City |
| 49 | `S_CITY2` | CHAR | 40 |  | District |
| 50 | `S_COUNTRY` | CHAR | 3 |  | Country Key |
| 51 | `S_STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 52 | `S_POST_CODE1` | CHAR | 10 |  | City postal code |
| 53 | `STR_ERG2_VBS` | CHAR | 40 |  | Street 3 |
| 54 | `STR_ERG4_VBS` | CHAR | 40 |  | Street 5 |
| 55 | `S_CHI_ADD_IND` | CHAR | 1 |  | Chinese Supply address indicator |
| 56 | `OVERDUE` | CURR | 13 |  | Overdue Charge |
| 57 | `LATE_PAYMENT` | CURR | 13 |  | Late Payment Charge |
| 58 | `OVERDUE_DEPOSIT` | CURR | 13 |  | Overdue Deposit |
| 59 | `UP_TO_DATE` | DATS | 8 |  | Payment include up to date |
| 60 | `AMOUNT_DUE` | CURR | 13 |  | Total amount due |
| 61 | `EXT_DUE_DATE` | DATS | 8 |  | Extended Due date |
| 62 | `BARCODE` | CHAR | 32 |  | Barcode for a bill |
| 63 | `WA_OCR` | CHAR | 31 |  | OCR code for a bill |
| 64 | `WAERS` | CUKY | 5 |  | Currency Key |
| 65 | `GOV_SUB_DUN_MSG` | CHAR | 1 |  | Government Subsidy Dunning Message |
| 66 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |

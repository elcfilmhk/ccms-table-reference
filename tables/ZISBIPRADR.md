# ZISBIPRADR
**Description:** Premise Address Structure
**Total Fields:** 22
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_premise_address========ft`
- `ziscrm0038`
- `ziscs0135`
- `ziscs0475_eec`
- `zisfi0146`
- `zisfi0148`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONTRACT` | CHAR | 10 |  | Contract |
| 2 | `STREET_3` | CHAR | 40 |  | Street 3 |
| 3 | `STREET` | CHAR | 60 |  | Street |
| 4 | `STREET_2` | CHAR | 40 |  | Street 2 |
| 5 | `STREET_4` | CHAR | 40 |  | Street 4 |
| 6 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 7 | `REGION` | CHAR | 40 |  | City |
| 8 | `DISTRICT` | CHAR | 40 |  | District |
| 9 | `ADDRESS_GUID` | CHAR | 32 |  | GUID of a Business Partner Address (CHAR 32) |
| 10 | `TELEPHONE` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 11 | `EXTENSION` | CHAR | 10 |  | Telephone no.: Extension |
| 12 | `CONSNUMBER` | NUMC | 3 |  | Sequence Number |
| 13 | `STREET_3_M` | CHAR | 40 |  | Street 3 |
| 14 | `STREET_M` | CHAR | 60 |  | Street |
| 15 | `STREET_2_M` | CHAR | 40 |  | Street 2 |
| 16 | `STREET_4_M` | CHAR | 40 |  | Street 4 |
| 17 | `HOUSE_NUM1_M` | CHAR | 10 |  | House Number |
| 18 | `REGION_M` | CHAR | 40 |  | City |
| 19 | `DISTRICT_M` | CHAR | 40 |  | District |
| 20 | `MOVE_OUT_DATE` | DATS | 8 |  | Move-Out Date |
| 21 | `MOVE_IN_DATE` | DATS | 8 |  | Move-In Date |
| 22 | `ADDRESS_ERROR` | CHAR | 1 |  | Address Error |

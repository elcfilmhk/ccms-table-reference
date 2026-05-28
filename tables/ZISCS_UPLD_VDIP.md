# ZISCS_UPLD_VDIP
**Description:** Table to hold Voltage-Dip calls
**Total Fields:** 23
**Key Fields:** MANDT, ORIGUPLDID_VDIP, SRC_SYS, IND_TYPE

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORIGUPLDID_VDIP` | NUMC | 10 | 🔑 | Original Upload Vdip Id |
| 3 | `SRC_SYS` | CHAR | 20 | 🔑 | Source System |
| 4 | `IND_TYPE` | CHAR | 20 | 🔑 | Event type of the uploaded event |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `PREMISE` | CHAR | 10 |  | Premise |
| 7 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 8 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 9 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 10 | `STREET` | CHAR | 60 |  | Street |
| 11 | `CITY1` | CHAR | 40 |  | City |
| 12 | `CITY2` | CHAR | 40 |  | District |
| 13 | `CITY2_M` | CHAR | 40 |  | District |
| 14 | `CITY1_M` | CHAR | 40 |  | City |
| 15 | `STREET_M` | CHAR | 60 |  | Street |
| 16 | `HOUSE_NUM1_M` | CHAR | 10 |  | House Number |
| 17 | `STR_SUPPL1_M` | CHAR | 40 |  | Street 2 |
| 18 | `STR_ERG4` | CHAR | 40 |  | Street 5 |
| 19 | `ACTUAL_INTR_DT` | CHAR | 14 |  | Interruption Datetime (Actual) |
| 20 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 21 | `CREATED_DT` | CHAR | 14 |  | Created Datetime |
| 22 | `CHANGED_BY` | CHAR | 12 |  | Changed By |
| 23 | `CHANGED_DT` | CHAR | 14 |  | Changed Datetime |

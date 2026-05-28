# ZISCS_CALL_VDIP
**Description:** Table to hold Voltage-Dip calls
**Total Fields:** 29
**Key Fields:** MANDT, ORIGCALLID_VDIP

## Programs Using This Table
- `ziscs0460`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORIGCALLID_VDIP` | NUMC | 10 | 🔑 | Original Call ID |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `CONTACTPHONE` | CHAR | 32 |  | Contact Phone |
| 5 | `PREMISE` | CHAR | 10 |  | Premise |
| 6 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 7 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 8 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 9 | `STREET` | CHAR | 60 |  | Street |
| 10 | `CITY1` | CHAR | 40 |  | City |
| 11 | `CITY2` | CHAR | 40 |  | District |
| 12 | `CITY2_M` | CHAR | 40 |  | District |
| 13 | `CITY1_M` | CHAR | 40 |  | City |
| 14 | `STREET_M` | CHAR | 60 |  | Street |
| 15 | `HOUSE_NUM1_M` | CHAR | 10 |  | House Number |
| 16 | `STR_SUPPL1_M` | CHAR | 40 |  | Street 2 |
| 17 | `STR_ERG4` | CHAR | 40 |  | Street 5 |
| 18 | `ZZDATETIME` | CHAR | 14 |  | Call date/time received |
| 19 | `REPT_INTR_DT` | CHAR | 14 |  | Interruption Datetime (Reported) |
| 20 | `ZZINCOMING_CHNL` | CHAR | 1 |  | Incoming Channel |
| 21 | `ZZINCOMING_ID` | CHAR | 50 |  | Incoming ID |
| 22 | `INTR_CONFIRM_ST` | CHAR | 1 |  | 'Y': result='YES'; 'N': result='NO'; [blank]: no result yet |
| 23 | `ACTUAL_INTR_DT` | CHAR | 14 |  | Interruption Datetime (Actual) |
| 24 | `CONFIRM_BY` | CHAR | 12 |  | Volt-Dip Confirmation By |
| 25 | `CONFIRM_DT` | CHAR | 14 |  | Volt-Dip Confirmation Datetime |
| 26 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 27 | `CREATED_DT` | CHAR | 14 |  | Created Datetime |
| 28 | `CHANGED_BY` | CHAR | 12 |  | Changed By |
| 29 | `CHANGED_DT` | CHAR | 14 |  | Changed Datetime |

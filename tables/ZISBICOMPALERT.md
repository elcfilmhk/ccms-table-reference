# ZISBICOMPALERT
**Description:** Table for Consumption Alert
**Total Fields:** 72
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0195`
- `zisbi0196`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `BILLID` | CHAR | 2 |  | Bill ID |
| 7 | `KTOKL` | CHAR | 4 |  | Account class |
| 8 | `TRADE_GRP` | CHAR | 6 |  | High consumption trade group |
| 9 | `ACTPERIOD` | CHAR | 40 |  | Category of a period for previous billing |
| 10 | `COMP_PERIOD` | NUMC | 2 |  | No. Of Consumption Period |
| 11 | `X_PERC` | CURR | 13 |  | High Consumption - X Percentage |
| 12 | `Y_CONSECUTIVE` | CURR | 13 |  | High Consumption - Y Consecutive |
| 13 | `Z_THIS_CONSUMP` | CURR | 13 |  | High Consumption - Z (This Consumption) |
| 14 | `W_LAST_CONSUMP` | CURR | 13 |  | High Consumption - W (Last Consumption) |
| 15 | `ALERT_NATURE` | CHAR | 1 |  | Alert Nature |
| 16 | `EBILL_SENDER` | CHAR | 100 |  | Email sender address name |
| 17 | `EMAIL` | CHAR | 100 |  | Email |
| 18 | `FIRST_PERC_I` | CURR | 13 |  | Percentage Increase of First Period |
| 19 | `SEC_PERC_I` | CURR | 13 |  | Percentage Increase of Second Period |
| 20 | `FIRST_PERC_D` | CURR | 13 |  | Percentage Decrease of First Period |
| 21 | `SEC_PERC_D` | CURR | 13 |  | Percentage Decrease of Second Period |
| 22 | `CY_CUR_DAYS` | NUMC | 6 |  | Current Year Current No. of Consumption Days |
| 23 | `CY_PRE_DAYS` | NUMC | 6 |  | Current Year Previous No. Of Consumption Days |
| 24 | `PY_CUR_DAYS` | NUMC | 6 |  | Previous Year Current No. of Consumption Days |
| 25 | `PY_PRE_DAYS` | NUMC | 6 |  | Previous Year Previous No. Of Consumption Days |
| 26 | `CY_CUR_AB` | DATS | 8 |  | Current Year Current Billing Period From Date (CB From) |
| 27 | `CY_CUR_BIS` | DATS | 8 |  | Current Year Current Billing Period To Date (CB To) |
| 28 | `CY_CUR_AVG_COMP` | DEC | 16 |  | Current Year Current BP Average Consumption (CB Comp) |
| 29 | `CY_PREV_AB` | DATS | 8 |  | Current Year Previous Billing Period From Date (PB From) |
| 30 | `CY_PREV_BIS` | DATS | 8 |  | Current Year Previous Billing Period To Date (PB To) |
| 31 | `CY_PREV_AVG_COMP` | DEC | 16 |  | Current Year Previous BP Average Consumption (PB Comp) |
| 32 | `PY_CUR_AB` | DATS | 8 |  | Previous Year Current Billing Period From Date (PY CB From) |
| 33 | `PY_CUR_BIS` | DATS | 8 |  | Previous Year Current Billing Period To Date (PY CB To) |
| 34 | `PY_CUR_AVG_COMP` | DEC | 16 |  | Previous Year Current BP Average Consumption (PY CB  Comp) |
| 35 | `PY_PREV_AB` | DATS | 8 |  | Previous Year Previous Billing Period From Date (PB-1 From) |
| 36 | `PY_PREV_BIS` | DATS | 8 |  | Previous Year Previous Billing Period To Date (PB-1 To) |
| 37 | `PY_PREV_AVG_COMP` | DEC | 16 |  | Previous Year Previous BP Average Consumption (PB-1 Comp) |
| 38 | `COMP_DATE_01` | DATS | 8 |  | Consumption Date 01 |
| 39 | `COMP_DATE_02` | DATS | 8 |  | Consumption Date 02 |
| 40 | `COMP_DATE_03` | DATS | 8 |  | Consumption Date 03 |
| 41 | `COMP_DATE_04` | DATS | 8 |  | Consumption Date 04 |
| 42 | `COMP_DATE_05` | DATS | 8 |  | Consumption Date 05 |
| 43 | `COMP_DATE_06` | DATS | 8 |  | Consumption Date 06 |
| 44 | `COMP_DATE_07` | DATS | 8 |  | Consumption Date 07 |
| 45 | `COMP_DATE_08` | DATS | 8 |  | Consumption Date 08 |
| 46 | `COMP_DATE_09` | DATS | 8 |  | Consumption Date 09 |
| 47 | `COMP_DATE_10` | DATS | 8 |  | Consumption Date 10 |
| 48 | `COMP_DATE_11` | DATS | 8 |  | Consumption Date 11 |
| 49 | `COMP_DATE_12` | DATS | 8 |  | Consumption Date 12 |
| 50 | `COMP_DATE_13` | DATS | 8 |  | Consumption Date 13 |
| 51 | `COMP_DATE_14` | DATS | 8 |  | Consumption Date 14 |
| 52 | `AVG_COMP_01` | DEC | 16 |  | Consumption 01 |
| 53 | `AVG_COMP_02` | DEC | 16 |  | Consumption 02 |
| 54 | `AVG_COMP_03` | DEC | 16 |  | Consumption 03 |
| 55 | `AVG_COMP_04` | DEC | 16 |  | Consumption 04 |
| 56 | `AVG_COMP_05` | DEC | 16 |  | Consumption 05 |
| 57 | `AVG_COMP_06` | DEC | 16 |  | Consumption 06 |
| 58 | `AVG_COMP_07` | DEC | 16 |  | Consumption 07 |
| 59 | `AVG_COMP_08` | DEC | 16 |  | Consumption 08 |
| 60 | `AVG_COMP_09` | DEC | 16 |  | Consumption 09 |
| 61 | `AVG_COMP_10` | DEC | 16 |  | Consumption 10 |
| 62 | `AVG_COMP_11` | DEC | 16 |  | Consumption 11 |
| 63 | `AVG_COMP_12` | DEC | 16 |  | Consumption 12 |
| 64 | `AVG_COMP_13` | DEC | 16 |  | Consumption 13 |
| 65 | `AVG_COMP_14` | DEC | 16 |  | Consumption 14 |
| 66 | `TIPS1` | NUMC | 8 |  | Tips 1 |
| 67 | `TIPS2` | NUMC | 8 |  | Tips 2 |
| 68 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 69 | `ERZET` | TIMS | 6 |  | Entry time |
| 70 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 71 | `PRINT_DATE` | DATS | 8 |  | Print Date |
| 72 | `PRINT_TIME` | TIMS | 6 |  | System Time |

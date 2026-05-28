# ZIS_EEC_FITAPRV
**Description:** FiT Application Approval Data
**Total Fields:** 52
**Key Fields:** MANDT, RE_APP_NO, PROCESS

## Programs Using This Table
- `ziscs0208`
- `ziscs0507`
- `ziscs0518`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `PROCESS` | CHAR | 1 | 🔑 | Approval Process |
| 4 | `RE_AP_STATUS` | CHAR | 2 |  | Approval Status |
| 5 | `RE_AP_DATE` | DATS | 8 |  | Date of approval |
| 6 | `BH_APPROVER` | CHAR | 12 |  | Approver Branch Head |
| 7 | `BH_APR_DAT` | DATS | 8 |  | Approver BH date |
| 8 | `BH_APR_TIM` | TIMS | 6 |  | Approver BH time |
| 9 | `BH_APR_IND` | CHAR | 1 |  | BH approver indicator |
| 10 | `BH_APR_REM` | CHAR | 60 |  | BH Remarks |
| 11 | `CD_APPROVER` | CHAR | 12 |  | CD Approver |
| 12 | `CD_APR_DAT` | DATS | 8 |  | CD Approver date |
| 13 | `CD_APR_TIM` | TIMS | 6 |  | CD Approver time |
| 14 | `CD_APR_IND` | CHAR | 1 |  | CD approver indicator |
| 15 | `CD_APR_REM` | CHAR | 60 |  | CD Remarks |
| 16 | `CDE_APPROVER` | CHAR | 12 |  | CD Approver |
| 17 | `CDE_APR_DAT` | DATS | 8 |  | CD Approver date |
| 18 | `CDE_APR_TIM` | TIMS | 6 |  | CD Approver time |
| 19 | `CDE_APR_IND` | CHAR | 1 |  | CD approver indicator |
| 20 | `CDE_APR_REM` | CHAR | 60 |  | CD Remarks |
| 21 | `DH_APPROVER` | CHAR | 12 |  | DH Approver |
| 22 | `DH_APR_DAT` | DATS | 8 |  | DH Approver date |
| 23 | `DH_APR_TIM` | TIMS | 6 |  | DH Approver time |
| 24 | `DH_APR_IND` | CHAR | 1 |  | DH approver indicator |
| 25 | `DH_APR_REM` | CHAR | 60 |  | DH Remarks |
| 26 | `SD_CBD_APR` | CHAR | 12 |  | SD-CBD Approver |
| 27 | `SD_APR_DAT` | DATS | 8 |  | SD-CBD Approver date |
| 28 | `SD_APR_TIM` | TIMS | 6 |  | SD-CBD Approver time |
| 29 | `SD_APR_IND` | CHAR | 1 |  | SD-CBD approver indicator |
| 30 | `SD_APR_REM` | CHAR | 60 |  | SD-CBD  Remarks |
| 31 | `CCDO_APR_DAT` | DATS | 8 |  | CDDO Approver date |
| 32 | `CCDO_APR_TIM` | TIMS | 6 |  | CCDO Approver time |
| 33 | `CCDO_APR_IND` | CHAR | 1 |  | CCDO approver indicator |
| 34 | `CANCEL_DATE` | DATS | 8 |  | Cancel date |
| 35 | `CANCEL_BY` | CHAR | 12 |  | Cancelled by |
| 36 | `REQUESTOR` | CHAR | 12 |  | Requestor |
| 37 | `REQUEST_DATE` | DATS | 8 |  | Request date |
| 38 | `PRO_FIT_DATE` | DATS | 8 |  | Provisional FiT rate approved On |
| 39 | `ACT_FIT_DATE` | DATS | 8 |  | Actual FiT rate approved on |
| 40 | `PRE_FIT_AMT` | CURR | 13 |  | Amount |
| 41 | `PRO_FIT_AMT` | CURR | 13 |  | Amount |
| 42 | `ACT_FIT_AMT` | CURR | 13 |  | Amount |
| 43 | `CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 44 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 45 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 46 | `ERZET` | TIMS | 6 |  | Entry time |
| 47 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 48 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 49 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 50 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 51 | `FIRST_APP` | CHAR | 1 |  | First Initialization |
| 52 | `LAST_APPROVER` | CHAR | 12 |  | Name of person who approved data |

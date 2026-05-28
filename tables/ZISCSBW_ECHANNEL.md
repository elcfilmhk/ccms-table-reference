# ZISCSBW_ECHANNEL
**Description:** eChannel Termination
**Total Fields:** 32
**Key Fields:** MANDT, ERDAT, ERZET, ERNAM, FILE_TYPE, ZZCONTRACT_ACCNT, ZZMOVEOUTDOC, ZZCREATE_ON

## Programs Using This Table
- `ziscs0184`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 4 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 5 | `FILE_TYPE` | CHAR | 1 | 🔑 | File |
| 6 | `ZZCONTRACT_ACCNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 7 | `ZZMOVEOUTDOC` | CHAR | 12 | 🔑 | Existing future MO document number |
| 8 | `ZZCREATE_ON` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 9 | `ZZOLD_MO_DATE` | DATS | 8 |  | Existing future move out date |
| 10 | `ZZNEW_MO_DATE` | DATS | 8 |  | New move out date selected by customer |
| 11 | `ZZADDRESS` | CHAR | 200 |  | New address for refund and final bill mailing |
| 12 | `ZZREFUND_BY` | CHAR | 1 |  | Refund by |
| 13 | `ZZBANK_ID` | CHAR | 4 |  | Existing Bank ID |
| 14 | `ZZEXT_ADD` | CHAR | 20 |  | External address number |
| 15 | `ZZSTATUS` | CHAR | 1 |  | Status |
| 16 | `ZZTRAN_ID` | CHAR | 10 |  | CRM activity ID |
| 17 | `ZZEMAIL` | CHAR | 60 |  | Email |
| 18 | `ZZTEL` | CHAR | 8 |  | Tel. |
| 19 | `ZZCS_DISPATCH` | CHAR | 1 |  | The alert delivery method |
| 20 | `ZZHM` | CHAR | 1 |  | HM existence flag |
| 21 | `ZZHM_TYPE` | CHAR | 1 |  | Type of Home move relationship |
| 22 | `ZZTARGET_CA` | CHAR | 12 |  | Target contract account |
| 23 | `ZZHM_STATUS` | CHAR | 1 |  | Home move relationship creation status |
| 24 | `ZZEMPTY_TARGETCA` | CHAR | 1 |  | Target CA will be populated later |
| 25 | `ZZHM_MIDATE` | DATS | 8 |  | Move-in date of the Target CA |
| 26 | `ZZHM_TYPE_EXIST` | CHAR | 1 |  | Existing HM relationship |
| 27 | `ZZHM_TARGETCA_EX` | CHAR | 12 |  | Existing Target CA |
| 28 | `ACTION` | CHAR | 1 |  | Action |
| 29 | `MI_TXN` | CHAR | 10 |  | Move-in Transaction |
| 30 | `MI_CA` | CHAR | 12 |  | Target CA |
| 31 | `ERR_MSG` | CHAR | 100 |  | Error Message |
| 32 | `TYPE` | CHAR | 10 |  | Create/Change MO |

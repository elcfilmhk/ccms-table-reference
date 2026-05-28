# ZTERMINATECA
**Description:** Termination of Contract Account
**Total Fields:** 27
**Key Fields:** MANDT, ZZCONTRACT_ACCNT, ZZMOVEOUTDOC, ZZCREATE_ON

## Programs Using This Table
- `z_bapi_ciamid_mo_detail=======ft`
- `zcl_z_bapi_ciamid_mo_d_mpc`
- `ziscs0184`
- `ziscs0185`
- `ziscs0256`
- `ziscs0257`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZCONTRACT_ACCNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ZZMOVEOUTDOC` | CHAR | 12 | 🔑 | Existing future MO document number |
| 4 | `ZZCREATE_ON` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ZZOLD_MO_DATE` | DATS | 8 |  | Existing future move out date |
| 6 | `ZZNEW_MO_DATE` | DATS | 8 |  | New move out date selected by customer |
| 7 | `ZZADDRESS` | CHAR | 200 |  | New address for refund and final bill mailing |
| 8 | `ZZREFUND_BY` | CHAR | 1 |  | Refund by |
| 9 | `ZZBANK_ID` | CHAR | 4 |  | Existing Bank ID |
| 10 | `ZZEXT_ADD` | CHAR | 20 |  | External address number |
| 11 | `ZZSTATUS` | CHAR | 1 |  | Status |
| 12 | `ZZTRAN_ID` | CHAR | 10 |  | CRM activity ID |
| 13 | `ZZEMAIL` | CHAR | 60 |  | Email |
| 14 | `ZZTEL` | CHAR | 8 |  | Tel. |
| 15 | `ZZCS_DISPATCH` | CHAR | 1 |  | The alert delivery method |
| 16 | `ZZHM` | CHAR | 1 |  | HM existence flag |
| 17 | `ZZHM_TYPE` | CHAR | 1 |  | Type of Home move relationship |
| 18 | `ZZTARGET_CA` | CHAR | 12 |  | Target contract account |
| 19 | `ZZHM_STATUS` | CHAR | 1 |  | Home move relationship creation status |
| 20 | `ZZEMPTY_TARGETCA` | CHAR | 1 |  | Target CA will be populated later |
| 21 | `ZZHM_MIDATE` | DATS | 8 |  | Move-in date of the Target CA |
| 22 | `ZZHM_TYPE_EXIST` | CHAR | 1 |  | Existing HM relationship |
| 23 | `ZZHM_TARGETCA_EX` | CHAR | 12 |  | Existing Target CA |
| 24 | `ACTION` | CHAR | 1 |  | Action |
| 25 | `MI_TXN` | CHAR | 10 |  | Move-in Transaction |
| 26 | `MI_CA` | CHAR | 12 |  | Target CA |
| 27 | `CIAMID` | CHAR | 50 |  | CIAM ID |

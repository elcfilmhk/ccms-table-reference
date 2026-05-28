# ZISCS_VAL_PREMISE
**Description:** Return the status of premise for online move-in
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_val_premise============ft`
- `ziscs_sms02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZTYPE` | CHAR | 1 |  | Single-Character Flag |
| 2 | `ZZID` | CHAR | 20 |  | Message Class |
| 3 | `ZZNUMBER` | NUMC | 3 |  | Message Number |
| 4 | `ZZMESSAGE` | CHAR | 220 |  | Message Text |
| 5 | `ZZADDR_REQ` | CHAR | 1 |  | Single-Character Flag |
| 6 | `ZZFMOREQ` | CHAR | 1 |  | Forced move-out request status |
| 7 | `ZZPAUSZDAT` | DATS | 8 |  | Pending Move-Out Date |
| 8 | `ZZSURNAME` | CHAR | 80 |  | Business Partner Name (English) |
| 9 | `ZZFULLNAME` | CHAR | 80 |  | Business Partner Name (English) |

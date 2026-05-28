# ZCSESISTR1
**Description:** iNPUT STRUCTURE FOR Z_ISDCS_UPDATE_ESERVICE_HDR
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_update_eservice_hdr====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `TYPE` | CHAR | 1 |  | Type of eService |
| 3 | `CHANNEL` | CHAR | 1 |  | Dispatch |
| 4 | `STATUS` | CHAR | 1 |  | Status |
| 5 | `MODIFIED_TMST` | CHAR | 14 |  | Change Date |
| 6 | `AENAM` | CHAR | 12 |  | Change By |
| 7 | `DEL` | CHAR | 1 |  | If 'Y' then delete the record. |

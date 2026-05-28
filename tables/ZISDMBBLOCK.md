# ZISDMBBLOCK
**Description:** DM Block Table
**Total Fields:** 15
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0273`
- `zisdm0204`
- `zisdm0205`
- `zisdm0206`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
| 7 | `IDAT2` | DATS | 8 |  | Technical completion date |
| 8 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 9 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 10 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 11 | `NEXT_ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 12 | `ZZBO` | CHAR | 1 |  | Status of Billing Order |
| 13 | `ZZOSTATUS` | CHAR | 1 |  | Service Order Status in Outsort table |
| 14 | `ZZSTATUS` | CHAR | 1 |  | DM Outsort Status - Order completion flag |
| 15 | `SO_MODIFIED_DAT` | DATS | 8 |  | SO Last Modified Date |

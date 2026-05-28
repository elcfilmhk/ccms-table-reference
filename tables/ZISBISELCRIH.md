# ZISBISELCRIH
**Description:** History of ZISBISELCRI
**Total Fields:** 22
**Key Fields:** MANDT, ARCHIVE_DATE, SELCRI_NO

## Programs Using This Table
- `zisbi0138`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ARCHIVE_DATE` | DATS | 8 | 🔑 | Date of Archive |
| 3 | `SELCRI_NO` | NUMC | 10 | 🔑 | The selection criteria number |
| 4 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 5 | `MESSAGE_NO` | NUMC | 10 |  | Message number |
| 6 | `INSERT_NO` | NUMC | 10 |  | Insert Number |
| 7 | `BATCH_NO` | NUMC | 10 |  | Batch Number |
| 8 | `LANGU` | CHAR | 1 |  | The bill language |
| 9 | `DISPTYPE` | CHAR | 100 |  | The Dispatch Control |
| 10 | `VKONT` | CHAR | 255 |  | Contract Account |
| 11 | `VERTRAG` | CHAR | 255 |  | Contract |
| 12 | `GPART` | CHAR | 255 |  | Business Partner |
| 13 | `TARIFTYP` | CHAR | 255 |  | Tariff type |
| 14 | `OPBEL` | CHAR | 255 |  | Print Document Number |
| 15 | `EZAWE` | CHAR | 50 |  | Payment Method |
| 16 | `BILL_TYPE` | CHAR | 100 |  | Bill type |
| 17 | `DELETE_FLAG` | CHAR | 1 |  | Delete Flag. |
| 18 | `VALID_TO` | DATS | 8 |  | Valid To Date |
| 19 | `VALID_FROM` | DATS | 8 |  | Valid From Date |
| 20 | `TPLNR` | CHAR | 255 |  | Connection Object |
| 21 | `ZZDELIVERY` | CHAR | 21 |  | Delivery Method |
| 22 | `CUSTOMER_TYPE` | CHAR | 1 |  | Customer Type |

# ZISBISELCRI
**Description:** Selection criteria for bill inserts messaging and batching
**Total Fields:** 21
**Key Fields:** MANDT, SELCRI_NO

## Programs Using This Table
- `zis_batch_insert_message======ft`
- `zisbi0003`
- `zisbi0005`
- `zisbi0010`
- `zisbi0059`
- `zisbi0060`
- `zisbi0093`
- `zisbi0138`
- `zisbi_conv_selcri_temp`
- `ziscs0288`
- `zisdm0035`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SELCRI_NO` | NUMC | 10 | 🔑 | The selection criteria number |
| 3 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 4 | `MESSAGE_NO` | NUMC | 10 |  | Message number |
| 5 | `INSERT_NO` | NUMC | 10 |  | Insert Number |
| 6 | `BATCH_NO` | NUMC | 10 |  | Batch Number |
| 7 | `LANGU` | CHAR | 1 |  | The bill language |
| 8 | `DISPTYPE` | CHAR | 100 |  | The Dispatch Control |
| 9 | `VKONT` | CHAR | 255 |  | Contract Account |
| 10 | `VERTRAG` | CHAR | 255 |  | Contract |
| 11 | `GPART` | CHAR | 255 |  | Business Partner |
| 12 | `TARIFTYP` | CHAR | 255 |  | Tariff type |
| 13 | `OPBEL` | CHAR | 255 |  | Print Document Number |
| 14 | `EZAWE` | CHAR | 50 |  | Payment Method |
| 15 | `BILL_TYPE` | CHAR | 100 |  | Bill type |
| 16 | `DELETE_FLAG` | CHAR | 1 |  | Delete Flag. |
| 17 | `VALID_TO` | DATS | 8 |  | Valid To Date |
| 18 | `VALID_FROM` | DATS | 8 |  | Valid From Date |
| 19 | `TPLNR` | CHAR | 255 |  | Connection Object |
| 20 | `ZZDELIVERY` | CHAR | 21 |  | Delivery Method |
| 21 | `CUSTOMER_TYPE` | CHAR | 1 |  | Customer Type |

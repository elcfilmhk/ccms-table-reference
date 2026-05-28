# ZISCS_ZMI_ORDER
**Description:** Table for ZMI order from completed ZME order
**Total Fields:** 29
**Key Fields:** MANDT, ZME_AUFNR

## Programs Using This Table
- `ziscs0466`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZME_AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ZME_AUART` | CHAR | 4 |  | Order Type |
| 4 | `ZME_ILART` | CHAR | 3 |  | Maintenance activity type |
| 5 | `ZME_INGPR` | CHAR | 3 |  | Planner Group for Customer Service and Plant Maintenance |
| 6 | `ZME_ERDAT` | DATS | 8 |  | Created on |
| 7 | `ZME_IDAT2` | DATS | 8 |  | Technical completion date |
| 8 | `ZMI_AUFNR` | CHAR | 12 |  | Order Number |
| 9 | `ZMI_AUART` | CHAR | 4 |  | Order Type |
| 10 | `ZMI_ILART` | CHAR | 3 |  | Maintenance activity type |
| 11 | `ZMI_INGPR` | CHAR | 3 |  | Planner Group for Customer Service and Plant Maintenance |
| 12 | `ZMI_ERDAT` | DATS | 8 |  | Created on |
| 13 | `ZMI_IDAT2` | DATS | 8 |  | Technical completion date |
| 14 | `TPLNR` | CHAR | 30 |  | Functional Location |
| 15 | `VAPLZ` | CHAR | 8 |  | Work Center |
| 16 | `KUNUM` | CHAR | 10 |  | Customer Number |
| 17 | `EQFNR` | CHAR | 30 |  | Sort field |
| 18 | `PREMS` | CHAR | 10 |  | Premise |
| 19 | `ANLAGE` | CHAR | 10 |  | Installation |
| 20 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 21 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 22 | `SERNR` | CHAR | 18 |  | Serial Number |
| 23 | `OBKNR` | INT4 | 10 |  | Object list number |
| 24 | `EQUNR_REPLACED` | CHAR | 18 |  | Equipment Number |
| 25 | `SERNR_REPLACED` | CHAR | 18 |  | Serial Number |
| 26 | `BATCH_RUN_DATE` | DATS | 8 |  | Batch Run Date |
| 27 | `ERNAM` | CHAR | 12 |  | Record Creator |
| 28 | `RECORD_STATUS` | CHAR | 1 |  | Record status (S = Success / P = Problem / F = Fail) |
| 29 | `REMARK` | CHAR | 100 |  | Remark |

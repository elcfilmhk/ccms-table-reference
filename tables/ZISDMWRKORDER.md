# ZISDMWRKORDER
**Description:** Table for Service Order creation approval
**Total Fields:** 27
**Key Fields:** MANDT, GUID

## Programs Using This Table
- `zisdm_so_approval`
- `zisdm_so_create`
- `zisdm_so_update`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GUID` | RAW | 16 | 🔑 | Globally Unique Identifier |
| 3 | `AUFNR` | CHAR | 12 |  | Order Number |
| 4 | `AUART` | CHAR | 4 |  | Sales Document Type |
| 5 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 6 | `BSTKD` | CHAR | 35 |  | Customer Purchase Order Number |
| 7 | `INGRP` | CHAR | 3 |  | Planner Group for Customer Service and Plant Maintenance |
| 8 | `EQFNR` | CHAR | 30 |  | Sort field |
| 9 | `GSTRP` | DATS | 8 |  | Basic start date |
| 10 | `GLTRP` | DATS | 8 |  | Basic finish date |
| 11 | `LTEXT` | STRG | 0 |  | Clevest Long Text - Limited |
| 12 | `ORDER_STATUS` | CHAR | 5 |  | Object status |
| 13 | `TPLNR` | CHAR | 30 |  | Functional Location |
| 14 | `SERNR` | CHAR | 18 |  | Serial Number |
| 15 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 16 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 17 | `WORKER_ID` | CHAR | 12 |  | User Name |
| 18 | `RSAMP` | NUMC | 2 |  | Random sample % to be created |
| 19 | `DEV_LOC_OR_DEV` | CHAR | 1 |  | Device or Device Location |
| 20 | `APPROVER_ID` | CHAR | 12 |  | Approver ID |
| 21 | `APPROVED_ON` | DATS | 8 |  | Approved On |
| 22 | `STATUS` | CHAR | 1 |  | Status |
| 23 | `CR_MO` | CHAR | 1 |  | Create/Modify |
| 24 | `CREATION_MODE` | CHAR | 1 |  | SO Creation Mode |
| 25 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 26 | `CREATED_ON` | DATS | 8 |  | Created On |
| 27 | `RS_ORDER` | CHAR | 12 |  | Random Sample Order ID |

# ZISCSSSR_PRG_GAD
**Description:** SSR Program Contract Account Assigned Gadgets
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, PROGRAM_ID, ITEM_NUMBER

## Programs Using This Table
- `zcl_ssr_program`
- `zrca_ssr_cust_extract`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PROGRAM_ID` | CHAR | 10 | 🔑 | Program ID |
| 4 | `ITEM_NUMBER` | NUMC | 4 | 🔑 | Item Number |
| 5 | `GADGET` | CHAR | 30 |  | SSR Program Smart Gadget |
| 6 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |

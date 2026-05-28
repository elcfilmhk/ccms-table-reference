# ZISCS_EA_PRDET
**Description:** To store details required for PR creation
**Total Fields:** 32
**Key Fields:** MANDT, OUTLINE_AGREEMENT, MATERIAL_GROUP, SERVICE_NO

## Programs Using This Table
- `z_ea_pr_create_rfc============ft`
- `z_iscseec_create_pr===========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OUTLINE_AGREEMENT` | CHAR | 10 | 🔑 | Number of principal purchase agreement |
| 3 | `MATERIAL_GROUP` | CHAR | 9 | 🔑 | Material Group |
| 4 | `SERVICE_NO` | CHAR | 18 | 🔑 | Activity Number |
| 5 | `AGMT_ITEM` | NUMC | 5 |  | Item number of principal purchase agreement |
| 6 | `PURCHASE_GROUP` | CHAR | 3 |  | Purchasing Group |
| 7 | `PURCHASE_ORGANISATION` | CHAR | 4 |  | Purchasing Organization |
| 8 | `PLANT` | CHAR | 4 |  | Plant |
| 9 | `INTERNAL_ORDER` | CHAR | 12 |  | Order Number |
| 10 | `BUSINESS_AREA` | CHAR | 4 |  | Business Area |
| 11 | `CO_AREA` | CHAR | 4 |  | Controlling Area |
| 12 | `QUANTITY` | QUAN | 13 |  | Purchase requisition quantity |
| 13 | `DELIVERY_DATE` | DATS | 8 |  | Item delivery date |
| 14 | `PURCHASE_REQUISITION_PRICE` | CURR | 11 |  | Price in Purchase Requisition |
| 15 | `ITEM_CATEGORY` | CHAR | 1 |  | Item category in purchasing document |
| 16 | `ACCOUNT_ASSIGNMENT_CATEGORY` | CHAR | 1 |  | Account Assignment Category |
| 17 | `NET_VALUE` | CURR | 11 |  | Net Value of Item |
| 18 | `GL_ACCOUNT_NO` | CHAR | 10 |  | G/L Account Number |
| 19 | `NET_PRICE` | CURR | 11 |  | Net Price |
| 20 | `FIXED_VENDOR` | CHAR | 10 |  | Fixed vendor |
| 21 | `FREE_TEXT` | CHAR | 40 |  | Free Text |
| 22 | `COSTCENTER` | CHAR | 10 |  | Cost Center |
| 23 | `CURRENCY` | CUKY | 5 |  | Currency Key |
| 24 | `PR_TYPE` | CHAR | 4 |  | Order Type (Purchasing) |
| 25 | `VALID_FROM` | DATS | 8 |  | Valid from |
| 26 | `VALID_TO` | DATS | 8 |  | Valid to |
| 27 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 28 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 29 | `ERZET` | TIMS | 6 |  | Entry time |
| 30 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 31 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 32 | `AEZET` | TIMS | 6 |  | Time last change was made |

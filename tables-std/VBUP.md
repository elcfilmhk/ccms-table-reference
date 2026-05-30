# `VBUP`

**Description:** Sales Document Item Status — item status
**Category:** Standard SAP Table
**References:** 4 SELECT statements across 4 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbup/) — validated 2026-05-30, schema v1.0
**Schema fields:** 50 fields | **Data types:** CHAR(50)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `RFSTA` | RFSTA | — | CHAR | 1 | 0 | Reference status |
| `RFGSA` | RFGSA | — | CHAR | 1 | 0 | Overall status of reference |
| `BESTA` | BESTA | — | CHAR | 1 | 0 | Confirmation Status of Document Item |
| `LFSTA` | LFSTA | — | CHAR | 1 | 0 | Delivery status |
| `LFGSA` | LFGSA | — | CHAR | 1 | 0 | Overall delivery status of the item |
| `WBSTA` | WBSTA | — | CHAR | 1 | 0 | Goods movement status |
| `FKSTA` | FKSTA | — | CHAR | 1 | 0 | Billing status of delivery-related billing documents |
| `FKSAA` | FKSAA | — | CHAR | 1 | 0 | Billing Status for Order-Related Billing Documents |
| `ABSTA` | ABSTA_VB | — | CHAR | 1 | 0 | Rejection status for SD item |
| `GBSTA` | GBSTA | — | CHAR | 1 | 0 | Overall processing status of the SD document item |
| `KOSTA` | KOSTA | — | CHAR | 1 | 0 | Picking status/Putaway status |
| `LVSTA` | LVSTA | — | CHAR | 1 | 0 | Status of warehouse management activities |
| `UVALL` | UVALL_UP | — | CHAR | 1 | 0 | General Incompletion Status of Item |
| `UVVLK` | UVVLK_UP | — | CHAR | 1 | 0 | Incompletion status of the item with regard to delivery |
| `UVFAK` | UVFAK_UP | — | CHAR | 1 | 0 | Item Incompletion Status with Respect to Billing |
| `UVPRS` | UVPRS_UP | — | CHAR | 1 | 0 | Pricing for item is incomplete |
| `FKIVP` | FKIVP | — | CHAR | 1 | 0 | Intercompany Billing Status |
| `UVP01` | UVP01 | — | CHAR | 1 | 0 | Customer reserves 1: Item status |
| `UVP02` | UVP02 | — | CHAR | 1 | 0 | Customer reserves 2: Item status |
| `UVP03` | UVP03 | — | CHAR | 1 | 0 | Item reserves 3: Item status |
| `UVP04` | UVP04 | — | CHAR | 1 | 0 | Item reserves 4: Item status |
| `UVP05` | UVP05 | — | CHAR | 1 | 0 | Customer reserves 5: Item status |
| `PKSTA` | PKSTA | — | CHAR | 1 | 0 | Packing status of item |
| `KOQUA` | KOQUA | — | CHAR | 1 | 0 | Confirmation status of picking/putaway |
| `COSTA` | COSTA_D | — | CHAR | 1 | 0 | Confirmation status for ALE |
| `CMPPI` | CMPSI | — | CHAR | 1 | 0 | Status of credit check against financial document |
| `CMPPJ` | CMPSJ | — | CHAR | 1 | 0 | Status of credit check against export credit insurance |
| `UVPIK` | UVPIP_UP | — | CHAR | 1 | 0 | Incomplete status of item for picking/putaway |
| `UVPAK` | UVPAP_UP | — | CHAR | 1 | 0 | Incomplete status of item for packaging |
| `UVWAK` | UVWAP_UP | — | CHAR | 1 | 0 | Incomplete status of item regarding goods issue |
| `DCSTA` | DCSTA | — | CHAR | 1 | 0 | Delay status |
| `RRSTA` | RR_STATUS | — | CHAR | 1 | 0 | Revenue determination status |
| `VLSTP` | VLSTP | — | CHAR | 1 | 0 | Decentralized whse processing |
| `FSSTA` | FSSTA | — | CHAR | 1 | 0 | Billing block status for items |
| `LSSTA` | LSSTA | — | CHAR | 1 | 0 | Delivery block status for item |
| `PDSTA` | PDSTA | — | CHAR | 1 | 0 | POD status on item level |
| `MANEK` | MANEK | — | CHAR | 1 | 0 | Manual Completion of Contract |
| `HDALL` | /SPE/INB_HDALL_ITM | — | CHAR | 1 | 0 | Inbound Delivery Item Not Yet Complete (on Hold) |
| `LTSPS` | /SAPHT/SW_LTSPS | — | CHAR | 1 | 0 | Indicator : stockable type switched into standard product |
| `MILL_VS_VSSTA` | MILL_VS_VSSTA | — | CHAR | 1 | 0 | Status of sales order item |
| `OIFINAL` | OID_FINAL | — | CHAR | 1 | 0 | Final Delivery Indicator |
| `OIINVCST1` | OIA_INVCS1 | — | CHAR | 1 | 0 | Status of invoice cycle 1 |
| `OIINVCST2` | OIA_INVCS2 | — | CHAR | 1 | 0 | Status of invoice cycle 2 |
| `OIINVCST3` | OIA_INVCS3 | — | CHAR | 1 | 0 | Status of invoice cycle 3 |
| `OIINVCST4` | OIA_INVCS4 | — | CHAR | 1 | 0 | Status of invoice cycle 4 |
| `OIINVCST5` | OIA_INVCS5 | — | CHAR | 1 | 0 | Status of invoice cycle 5 |
| `OIINVCST6` | OIA_INVCS6 | — | CHAR | 1 | 0 | Status of invoice cycle 6 |
| `OIINVCST7` | OIA_INVCS7 | — | CHAR | 1 | 0 | Status of invoice cycle 7 |
| `OIINVCST8` | OIA_INVCS8 | — | CHAR | 1 | 0 | Status of invoice cycle 8 |
| `OIINVCST9` | OIA_INVCS9 | — | CHAR | 1 | 0 | Status of invoice cycle 9 |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | VBUP | MANDT | T000 |  | |
| `VBELN` | VBUP | MANDT | VBUK |  | |
| `VBELN` | VBUP | VBELN | VBUK |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00012.txt`
- `zissd00024.txt`
- `zsdisqry03.txt`
- `zsdisqry04.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
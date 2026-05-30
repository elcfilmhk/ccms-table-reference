# `VBUK`

**Description:** Sales Document Status — status header
**Category:** Standard SAP Table
**References:** 2 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbuk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 84 fields | **Data types:** CHAR(82), DATS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `RFSTK` | RFSTK | — | CHAR | 1 | 0 | Reference document header status |
| `RFGSK` | RFGSK | — | CHAR | 1 | 0 | Total reference status of all items |
| `BESTK` | BESTK | — | CHAR | 1 | 0 | Confirmation status |
| `LFSTK` | LFSTK | — | CHAR | 1 | 0 | Delivery status |
| `LFGSK` | LKGSK | — | CHAR | 1 | 0 | Overall delivery status for all items |
| `WBSTK` | WBSTK | — | CHAR | 1 | 0 | Total goods movement status |
| `FKSTK` | FKSTK | — | CHAR | 1 | 0 | Billing status |
| `FKSAK` | FKSAK | — | CHAR | 1 | 0 | Billing status (order-related billing document) |
| `BUCHK` | BUCHK | — | CHAR | 1 | 0 | Posting Status of Billing Document |
| `ABSTK` | ABSTK | — | CHAR | 1 | 0 | Overall rejection status of all document items |
| `GBSTK` | GBSTK | — | CHAR | 1 | 0 | Overall processing status of document |
| `KOSTK` | KOSTK | — | CHAR | 1 | 0 | Overall picking / putaway status |
| `LVSTK` | LVSTK | — | CHAR | 1 | 0 | Overall status of warehouse management activities |
| `UVALS` | UVALL_SU | — | CHAR | 1 | 0 | Total incompletion status of all items in general |
| `UVVLS` | UVVLS_SU | — | CHAR | 1 | 0 | Total incompletion status of all items: Delivery |
| `UVFAS` | UVFAK_SU | — | CHAR | 1 | 0 | Total incompletion status of all items: Billing |
| `UVALL` | UVALL_UK | — | CHAR | 1 | 0 | General incompletion status of the header |
| `UVVLK` | UVVLK_UK | — | CHAR | 1 | 0 | Header incompletion status concerning delivery |
| `UVFAK` | UVFAK_UK | — | CHAR | 1 | 0 | Header incompletion status with respect to billing |
| `UVPRS` | UVPRS_UK | — | CHAR | 1 | 0 | Document is incomplete with respect to pricing |
| `VBTYP` | VBTYP | — | CHAR | 1 | 0 | SD document category |
| `VBOBJ` | VBOBJ | — | CHAR | 1 | 0 | SD document object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `FKIVK` | FKIVK | — | CHAR | 1 | 0 | Billing totals status for intercompany billing |
| `RELIK` | RELIK | — | CHAR | 1 | 0 | Invoice list status of billing document |
| `UVK01` | UVK01 | — | CHAR | 1 | 0 | Customer reserves 1: Header status |
| `UVK02` | UVK02 | — | CHAR | 1 | 0 | Customer reserves 2: Header status |
| `UVK03` | UVK03 | — | CHAR | 1 | 0 | Customer reserves 3: Header status |
| `UVK04` | UVK04 | — | CHAR | 1 | 0 | Custmer reserves 4: Header status |
| `UVK05` | UVK05 | — | CHAR | 1 | 0 | Customer reserves 5: Header status |
| `UVS01` | UVS01 | — | CHAR | 1 | 0 | Customer reserves 1: Sum of all items |
| `UVS02` | UVS02 | — | CHAR | 1 | 0 | Customer reserves 2: Sum of all items |
| `UVS03` | UVS03 | — | CHAR | 1 | 0 | Customer reserves 3: Sum of all items |
| `UVS04` | UVS04 | — | CHAR | 1 | 0 | Customer reserves 4: Sum of all items |
| `UVS05` | UVS05 | — | CHAR | 1 | 0 | Customer reserves 5: Sum of all items |
| `PKSTK` | PKSTK | — | CHAR | 1 | 0 | Overall packing status of all items |
| `CMPSA` | CMPSA | — | CHAR | 1 | 0 | Status of static credit limit check |
| `CMPSB` | CMPSB | — | CHAR | 1 | 0 | Status of dynamic credit limit check in the credit horizon |
| `CMPSC` | CMPSC | — | CHAR | 1 | 0 | Status of credit check against maximum document value |
| `CMPSD` | CMPSD | — | CHAR | 1 | 0 | Status of credit check against terms of payment |
| `CMPSE` | CMPSE | — | CHAR | 1 | 0 | Status of credit check against customer review date |
| `CMPSF` | CMPSF | — | CHAR | 1 | 0 | Status of credit check against open items due |
| `CMPSG` | CMPSG | — | CHAR | 1 | 0 | Status of credit check against oldest open items |
| `CMPSH` | CMPSH | — | CHAR | 1 | 0 | Status of credit check against highest dunning level |
| `CMPSI` | CMPSI | — | CHAR | 1 | 0 | Status of credit check against financial document |
| `CMPSJ` | CMPSJ | — | CHAR | 1 | 0 | Status of credit check against export credit insurance |
| `CMPSK` | CMPSK | — | CHAR | 1 | 0 | Status of credit check against payment card authorization |
| `CMPSL` | CMPSL | — | CHAR | 1 | 0 | Status of credit check of reserves 4 |
| `CMPS0` | CMPS0 | — | CHAR | 1 | 0 | Status of credit check for customer reserve 1 |
| `CMPS1` | CMPS1 | — | CHAR | 1 | 0 | Status of credit check for customer reserve 2 |
| `CMPS2` | CMPS2 | — | CHAR | 1 | 0 | Status of credit check for customer reserve 3 |
| `CMGST` | CMGST | — | CHAR | 1 | 0 | Overall status of credit checks |
| `TRSTA` | TRSTA | — | CHAR | 1 | 0 | Transportation planning status |
| `KOQUK` | KOQUK | — | CHAR | 1 | 0 | Status of pick confirmation |
| `COSTA` | COSTA_D | — | CHAR | 1 | 0 | Confirmation status for ALE |
| `SAPRL` | SAPRL | — | CHAR | 4 | 0 | SAP Release |
| `UVPAS` | UVPAK_SU | — | CHAR | 1 | 0 | Totals incomplete status for all items: packaging |
| `UVPIS` | UVPIK_SU | — | CHAR | 1 | 0 | Totals incomplete status for all items: Picking |
| `UVWAS` | UVWAK_SU | — | CHAR | 1 | 0 | Total incomplete status of all items: post goods movement |
| `UVPAK` | UVPAK_UK | — | CHAR | 1 | 0 | Header incomplete status for packaging |
| `UVPIK` | UVPIK_UK | — | CHAR | 1 | 0 | Header incomplete status for picking/putaway |
| `UVWAK` | UVWAK_UK | — | CHAR | 1 | 0 | Post header incomplete status for goods movement |
| `UVGEK` | UVGEK_UK | — | CHAR | 1 | 0 | UNUSED |
| `CMPSM` | CMPSM | — | CHAR | 1 | 0 | Credit check data is obsolete |
| `DCSTK` | DCSTK | — | CHAR | 1 | 0 | Delay status |
| `VESTK` | VESTK | — | CHAR | 1 | 0 | Handling Unit Placed in Stock |
| `VLSTK` | VLSTK | — | CHAR | 1 | 0 | Distribution Status (Decentralized Warehouse Processing) |
| `RRSTA` | RR_STATUS | — | CHAR | 1 | 0 | Revenue determination status |
| `BLOCK` | BLOCK_VB | — | CHAR | 1 | 0 | Indicator: Document preselected for archiving |
| `FSSTK` | FSSTK | — | CHAR | 1 | 0 | Overall billing block status |
| `LSSTK` | LSSTK_G | — | CHAR | 1 | 0 | Overall delivery block status |
| `SPSTG` | SPSTG | — | CHAR | 1 | 0 | Overall blocked status |
| `PDSTK` | PDSTK | — | CHAR | 1 | 0 | POD status on header level |
| `FMSTK` | FMSTK | — | CHAR | 1 | 0 | Status Funds Management |
| `MANEK` | MANEK | — | CHAR | 1 | 0 | Manual Completion of Contract |
| `SPE_TMPID` | /SPE/TMPID | — | CHAR | 1 | 0 | Temporary inbound delivery |
| `HDALL` | /SPE/INB_HDALL | — | CHAR | 1 | 0 | Inbound delivery header not yet complete (on Hold) |
| `HDALS` | /SPE/INB_HDALS | — | CHAR | 1 | 0 | At least one of ID items not yet complete (on Hold) |
| `CMPS_CM` | CMPS_CM | — | CHAR | 1 | 0 | Status of Credit Check SAP Credit Management |
| `CMPS_TE` | CMPS_TE | — | CHAR | 1 | 0 | Status of Technical Error SAP Credit Management |
| `VBTYP_EXT` | TDD_VBTYP_EXT | — | CHAR | 4 | 0 | Extension of SD Document Category |
| `OIG_SSTSF` | OIG_SSTSF | — | CHAR | 1 | 0 | TD Shipment Status (Functional) |
| `OI_SHIP` | — | — | CHAR | 10 | 0 | OI_SHIP |
| `OIC_NXTINV` | OIC_NXINV | — | DATS | 8 | 0 | Next billing date for invoice if status is provisional |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | VBUK | MANDT | T000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00113.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
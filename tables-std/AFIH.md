# `AFIH`

**Description:** Maintenance Order Header — PM order header
**Category:** Standard SAP Table
**References:** 45 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/afih/) — validated 2026-05-30, schema v1.0
**Schema fields:** 45 fields | **Data types:** CHAR(32), DATS(5), FLTP(1), INT4(2), NUMC(1), TIMS(3), UNIT(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ARTPR` | ARTPR | T356A | CHAR | 2 | 0 | Priority Type |
| `PRIOK` | PRIOK | T356 | CHAR | 1 | 0 | Priority |
| `EQUNR` | EQUNR | EQUI | CHAR | 18 | 0 | Equipment Number |
| `BAUTL` | BAUTL | MARA | CHAR | 18 | 0 | Assembly |
| `ILOAN` | ILOAN | ILOA | CHAR | 12 | 0 | Location and account assignment for technical object |
| `ILOAI` | ILOAI | — | CHAR | 1 | 0 | ILOA Individual |
| `ANLZU` | ANLZU | T357M | CHAR | 1 | 0 | Syst.Condition |
| `IWERK` | IWERK | T399I | CHAR | 4 | 0 | Maintenance Planning Plant |
| `INGPR` | INGRP | T024I | CHAR | 3 | 0 | Planner Group for Customer Service and Plant Maintenance |
| `APGRP` | VAGRP | T024A | CHAR | 3 | 0 | Responsible planner group/department |
| `PM_OBJTY` | PM_OBJTY | — | CHAR | 2 | 0 | Object Type of CIM Resources for Work Center |
| `GEWRK` | LGWID | CRID | NUMC | 8 | 0 | Object ID of the Work Center |
| `KUNUM` | KUNUM | KNA1 | CHAR | 10 | 0 | Customer Number |
| `ANING` | ANING | — | CHAR | 12 | 0 | Name of Person Reponsible for System |
| `GAUZT` | GAUZT | — | FLTP | 16 | 16 | Planned downtime in hours |
| `GAUEH` | MAUEH | T006 | UNIT | 3 | 0 | Unit for Breakdown Duration |
| `ANLBD` | ANLBD | — | DATS | 8 | 0 | Date until which the system is available |
| `ANLVD` | ANLVD | — | DATS | 8 | 0 | Date from which the system is available |
| `ANLBZ` | ANLBZ | — | TIMS | 6 | 0 | Time until which the system is available |
| `ANLVZ` | ANLVZ | — | TIMS | 6 | 0 | Time from Which System is Available |
| `INSPK` | INSPK | — | CHAR | 12 | 0 | Name of Person Responsible for Technical Inspection |
| `DATAN` | DATAN | — | DATS | 8 | 0 | Date of Technical Inspection |
| `WARPL` | WARPL | MPLA | CHAR | 12 | 0 | Maintenance Plan |
| `ABNUM` | ABNUM | — | INT4 | 10 | 0 | Maintenance Plan Call Number |
| `WAPOS` | WAPOS | — | CHAR | 16 | 0 | Maintenance item |
| `LAUFN` | LAUFN | AUFK | CHAR | 12 | 0 | Order number |
| `OBKNR` | OBJKNR | SER00 | INT4 | 10 | 0 | Object list number |
| `REVNR` | REVNI | T352R | CHAR | 8 | 0 | Revision for Plant Maintenance and Customer Service |
| `ADDAT` | ADDAT | — | DATS | 8 | 0 | PM Order: Reference Date |
| `ADUHR` | ADUHR | — | TIMS | 6 | 0 | Time of Reference Date |
| `IPHAS` | PM_PHASE | — | CHAR | 1 | 0 | Maintenance Processing Phase |
| `ILART` | ILA | T353I | CHAR | 3 | 0 | Maintenance activity type |
| `QMNUM` | QMNUM | QMEL | CHAR | 12 | 0 | Notification No |
| `HISDA` | HISDA | — | DATS | 8 | 0 | PM request: History date |
| `AKKNZ` | AKKNZ | — | CHAR | 1 | 0 | Order Category Indicator Plant Maintenance |
| `PLKNZ` | AUF_PLKNZ | — | CHAR | 1 | 0 | Maintenance order planning indicator |
| `SERIALNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `SERMAT` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `DEVICEID` | DEVICEID | — | CHAR | 40 | 0 | Additional Device Data |
| `SCREENTY` | SCRTP | TQBT | CHAR | 4 | 0 | Scenario or Subscreen Category |
| `ADPSP` | ADDCOMPARE_CORE | — | CHAR | 40 | 0 | Reference Element PM/PS |
| `RSUPG` | RSUPG | — | CHAR | 1 | 0 | Upgrade Order Indicator |
| `/ISDFPS/OBJNR` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `/ISDFPS/MEQUI` | /ISDFPS/MEQUI | — | CHAR | 18 | 0 | Master Equipment |
| `UII` | UII_CHAR72 | — | CHAR | 72 | 0 | Unique Item Identifier |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ANLZU` | AFIH | ANLZU | T357M |  | |
| `ANLZU` | SYST | MANDT | T357M |  | |
| `APGRP` | AFIH | IWERK | T024A |  | |
| `APGRP` | AFIH | APGRP | T024A |  | |
| `APGRP` | AFIH | MANDT | T024A |  | |
| `ARTPR` | AFIH | MANDT | T356A |  | |
| `ARTPR` | AFIH | ARTPR | T356A |  | |
| `AUFNR` | AFIH | MANDT | AUFK |  | |
| `AUFNR` | AFIH | AUFNR | AUFK |  | |
| `BAUTL` | AFIH | MANDT | MARA |  | |
| `BAUTL` | AFIH | BAUTL | MARA |  | |
| `EQUNR` | AFIH | MANDT | EQUI |  | |
| `EQUNR` | AFIH | EQUNR | EQUI |  | |
| `GAUEH` | AFIH | MANDT | T006 |  | |
| `GAUEH` | AFIH | GAUEH | T006 |  | |
| `GEWRK` | AFIH | GEWRK | CRID |  | |
| `GEWRK` | AFIH | MANDT | CRID |  | |
| `GEWRK` | AFIH | PM_OBJTY | CRID |  | |
| `ILART` | AFIH | MANDT | T353I |  | |
| `ILART` | AFIH | ILART | T353I |  | |
| `ILOAN` | AFIH | MANDT | ILOA |  | |
| `ILOAN` | AFIH | ILOAN | ILOA |  | |
| `INGPR` | AFIH | MANDT | T024I |  | |
| `INGPR` | AFIH | IWERK | T024I |  | |
| `INGPR` | AFIH | INGPR | T024I |  | |
| `IWERK` | AFIH | MANDT | T399I |  | |
| `IWERK` | AFIH | IWERK | T399I |  | |
| `KUNUM` | AFIH | MANDT | KNA1 |  | |
| `KUNUM` | AFIH | KUNUM | KNA1 |  | |
| `LAUFN` | AFIH | MANDT | AUFK |  | |
| `LAUFN` | AFIH | LAUFN | AUFK |  | |
| `MANDT` | AFIH | MANDT | T000 |  | |
| `OBKNR` | AFIH | OBKNR | SER00 |  | |
| `OBKNR` | SYST | MANDT | SER00 |  | |
| `PRIOK` | AFIH | ARTPR | T356 |  | |
| `PRIOK` | AFIH | PRIOK | T356 |  | |
| `PRIOK` | AFIH | MANDT | T356 |  | |
| `QMNUM` | AFIH | MANDT | QMEL |  | |
| `QMNUM` | AFIH | QMNUM | QMEL |  | |
| `REVNR` | AFIH | MANDT | T352R |  | |
| `REVNR` | AFIH | IWERK | T352R |  | |
| `REVNR` | AFIH | REVNR | T352R |  | |
| `SCREENTY` | AFIH | SCREENTY | TQBT |  | |
| `SERMAT` | AFIH | SERMAT | MARA |  | |
| `SERMAT` | AFIH | MANDT | MARA |  | |
| `WARPL` | AFIH | MANDT | MPLA |  | |
| `WARPL` | AFIH | WARPL | MPLA |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addat`, `aufnr`, `gewrk`, `ilart`, `iloan`, `iphas`, `priok`, `qmnum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `aufnr`, `ilart`

## Join Paths
- `AFIH.ILOA` → `EITR.ILOA` — Maint Order → Tech Location

## Programs Using This Table
- `method-check_open_order_exists.txt`
- `method-read_pmacttype.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_isusmorder_exch.txt`
- `z_validate_n_transfer_mt.txt`
- `zisbi0104.txt`
- `ziscrm0318forms.txt`
- `ziscs0016.txt`
- `ziscs0027.txt`
- `ziscs0153.txt`
- `ziscs0229.txt`
- `ziscs0507_f01.txt`
- `ziscs1119.txt`
- `ziscs_get_digital_customer.txt`
- `zisdh0026.txt`
- `zisdm0028.txt`
- `zisdm0043.txt`
- `zisdm0050.txt`
- `zisfi0005_dun.txt`
- `zisfi0009.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
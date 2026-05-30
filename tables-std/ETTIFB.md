# `ETTIFB`

**Description:** Installation Billing Item — billing line items
**Category:** Standard SAP Table
**References:** 10 SELECT statements across 7 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ettifb/) — validated 2026-05-30, schema v1.0
**Schema fields:** 46 fields | **Data types:** CHAR(29), CUKY(2), CURR(2), DATS(1), DEC(6), INT4(2), NUMC(4)

## Key Fields
`ADDRNUMBER`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BIS` | BISZEITSCH | — | DATS | 8 | 0 | Date at Which a Time Slice Expires |
| `TARIFART` | TARIFART | — | CHAR | 8 | 0 | Rate Type |
| `KONDIGR` | KONDIGR | — | CHAR | 10 | 0 | Rate fact group |
| `WERT1` | E_WERT1 | — | DEC | 16 | 7 | Entry value (installed value) for a device |
| `WERT2` | E_WERT2 | — | DEC | 16 | 7 | Value to be billed |
| `STRING1` | STRING1 | — | CHAR | 10 | 0 | First key field for operand value |
| `STRING2` | STRING2 | — | CHAR | 10 | 0 | Second key field for operand value |
| `STRING3` | STRING3 | — | CHAR | 1 | 0 | Third key field for operand value |
| `STRING4` | STRING4 | — | CHAR | 1 | 0 | Fourth key field for operand value |
| `ERSATZWERT` | ERSATZWERT | — | CHAR | 1 | 0 | Replacement value for operands |
| `BETRAG` | E_BETRAG | — | CURR | 13 | 2 | Currency-dependent amount |
| `WAERS` | WAERS | — | CUKY | 5 | 0 | Currency Key |
| `LOGIKZW` | LOGIKZW | — | NUMC | 18 | 0 | Logical register number |
| `LOGIKNR` | LOGIKNR | — | NUMC | 18 | 0 | Logical device number |
| `EQUNR` | REFV_EQUNR | — | CHAR | 18 | 0 | Allocation of reference value to equipment number |
| `ABRECH` | ABRECH | — | CHAR | 1 | 0 | Not relevant to billing |
| `GENWERT` | GENWERT | — | DEC | 16 | 6 | Contract demand limit |
| `VERGLREL` | VERGLREL | — | CHAR | 1 | 0 | Not comparison-relevant (connection) |
| `WDHFAKT` | WDHFAKT | — | INT4 | 10 | 0 | Repetition factor for reference values |
| `VTYP` | E_VTYP | — | CHAR | 4 | 0 | Contract category for heating installations |
| `LAGE` | LAGE | — | CHAR | 4 | 0 | Location of reference value |
| `LGZUSATZ` | LGZUSATZ | — | CHAR | 40 | 0 | Additional Information on Location |
| `HZBAUFRM` | HZBAUFRM | TE677 | CHAR | 4 | 0 | Description of a heating installation |
| `LEUCHTNR` | LEUCHTNR | — | CHAR | 10 | 0 | External lighting number |
| `BSSTATUS` | BSSTATUS | — | CHAR | 1 | 0 | Lighting belongs to the utility company |
| `WARTKOST` | WARTKOST | — | CHAR | 1 | 0 | Streetlights subject to maintenance costs |
| `ADDRNUMBER` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `ANZEINZ` | ANZEINZ | — | INT4 | 10 | 0 | Number of individual devices in a heating installation |
| `AUFLDSTG` | AUFLDSTG | TE679 | CHAR | 10 | 0 | Heating installation charging control |
| `INHALT` | E_INHALT | — | CHAR | 4 | 0 | Contents |
| `BZGBEZ` | BZGBEZ | — | CHAR | 30 | 0 | Reference value description deviates from operand descript. |
| `CONSUMPTION` | LIGHTCONSUMPTION | — | DEC | 16 | 7 | Consumption for streetlight |
| `ADDAMOUNT` | ADDAMOUNT | — | CURR | 13 | 2 | Additional flat-rate amount for a streetlight |
| `ADDAMOUNTWAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `TIMBASIS` | TIMBASIS | — | CHAR | 3 | 0 | Time Basis |
| `TIMTYP` | TIMTYP | — | CHAR | 1 | 0 | Time category (days or months) |
| `EIGENTUM` | EIGENTUM | — | CHAR | 2 | 0 | Owner |
| `CONTSHARE` | CONTSHARE | — | DEC | 31 | 14 | Container Portion |
| `EQUNR_WSTE` | EQUNR | — | CHAR | 18 | 0 | Equipment Number |
| `NO_UNITIES` | NO_UNITIES | — | NUMC | 6 | 0 | No. of premises |
| `BEHAELTER` | BEHAELTER | — | CHAR | 18 | 0 | Serial Number of Container |
| `BEH_TYPE` | BEH_TYPE | — | CHAR | 18 | 0 | Container category |
| `CLEAN_PROP` | EEWA_CLEAN_PROP | — | CHAR | 12 | 0 | Property |
| `PROPSHARE` | PROPSHARE | — | DEC | 31 | 14 | Property Portion |
| `BEHGRP` | BEHGRP | — | CHAR | 8 | 0 | Container Group |
| `IBASE` | IB_IBASE | — | NUMC | 18 | 0 | IBase: Number of the Installed Base/IBase |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDAMOUNTWAERS` | * |  | TCURC |  | |
| `ADDAMOUNTWAERS` | ETTIFB | ADDAMOUNTWAERS | TCURC |  | |
| `AUFLDSTG` | SY | MANDT | TE679 |  | |
| `AUFLDSTG` | ETTIFB | AUFLDSTG | TE679 |  | |
| `HZBAUFRM` | SY | MANDT | TE677 |  | |
| `HZBAUFRM` | ETTIFB | HZBAUFRM | TE677 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `anlage`, `bis`, `operand`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0016.txt`
- `zisbi0025.txt`
- `zisbi0025_1.txt`
- `zisbi0105.txt`
- `ziscs0049.txt`
- `ziscs_migration_unmetered_sp.txt`
- `zreprjt00.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
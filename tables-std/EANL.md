# `EANL`

**Description:** Installation — premise/installation master
**Category:** Standard SAP Table
**References:** 499 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eanl/) — validated 2026-05-30, schema v1.0
**Schema fields:** 23 fields | **Data types:** CHAR(21), DATS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `SPARTE` | SPARTE | TESPT | CHAR | 2 | 0 | Division |
| `VSTELLE` | VSTELLE | EVBS | CHAR | 10 | 0 | Premise |
| `ABLSPERR` | ABLSPERR | TE119 | CHAR | 2 | 0 | Reason for blocking meter reading |
| `BAPERTYP` | BAPERTYP | — | CHAR | 1 | 0 | Base period category |
| `ANSCHREI` | ANSCHREI | — | CHAR | 10 | 0 | Notification control for MR announcement/request |
| `SPEBENE` | SPEBENE | TE369 | CHAR | 2 | 0 | Voltage Level |
| `DRCKSTUF` | DRCKSTUF_GRID | TE696 | CHAR | 2 | 0 | Gas Pressure Level at Installation Level (Grid) |
| `ANLART` | ANLART | TE439 | CHAR | 4 | 0 | Installation type |
| `BEZUG` | BEZUG | — | CHAR | 1 | 0 | Reference |
| `ABLESARTST` | ABLESARTST | TE438 | CHAR | 8 | 0 | Control of perm. number of cust. MRs and autom. estimations |
| `NODISCONCT` | NODISCONCT | TE759 | CHAR | 4 | 0 | Reason for guarantee of supply |
| `SERVICE` | SERCODE | TECDE | CHAR | 4 | 0 | Service Type |
| `DEREGSTAT` | DEREGSTAT | TEDEREGSTAT | CHAR | 2 | 0 | Deregulation status |
| `INFOREL` | INFOREL | TEINFOREL | CHAR | 2 | 0 | Release Status for Installation Data |
| `ETIMEZONE` | EDM_TIMEZONE | TTZZ | CHAR | 6 | 0 | Time Zone for EDM Objects |
| `OUCONT` | OUCONT | — | CHAR | 1 | 0 | Outline Contract |
| `HOLICALID` | HOLICALID | — | CHAR | 2 | 0 | Public Holiday Calendar |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABLESARTST` | EANL | MANDT | TE438 |  | |
| `ABLESARTST` | EANL | ABLESARTST | TE438 |  | |
| `ABLSPERR` | EANL | MANDT | TE119 |  | |
| `ABLSPERR` | EANL | ABLSPERR | TE119 |  | |
| `ANLART` | EANL | MANDT | TE439 |  | |
| `ANLART` | EANL | ANLART | TE439 |  | |
| `DEREGSTAT` | EANL | MANDT | TEDEREGSTAT |  | |
| `DEREGSTAT` | EANL | DEREGSTAT | TEDEREGSTAT |  | |
| `DRCKSTUF` | SYST | MANDT | TE696 |  | |
| `DRCKSTUF` | EANL | DRCKSTUF | TE696 |  | |
| `ETIMEZONE` | EANL | MANDT | TTZZ |  | |
| `ETIMEZONE` | EANL | ETIMEZONE | TTZZ |  | |
| `INFOREL` | EANL | MANDT | TEINFOREL |  | |
| `INFOREL` | EANL | INFOREL | TEINFOREL |  | |
| `MANDT` | EANL | MANDT | T000 |  | |
| `NODISCONCT` | EANL | MANDT | TE759 |  | |
| `NODISCONCT` | EANL | NODISCONCT | TE759 |  | |
| `SERVICE` | EANL | SERVICE | TECDE |  | |
| `SERVICE` | EANL | MANDT | TECDE |  | |
| `SPARTE` | EANL | SPARTE | TESPT |  | |
| `SPARTE` | EANL | MANDT | TESPT |  | |
| `SPEBENE` | EANL | SPEBENE | TE369 |  | |
| `SPEBENE` | EANL | MANDT | TE369 |  | |
| `VSTELLE` | EANL | MANDT | EVBS |  | |
| `VSTELLE` | EANL | VSTELLE | EVBS |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABLSPERR`, `ANLAGE`, `VST`, `VSTELLE`, `ableinh`, `ablesartst`, `ablsperr`, `anlage`, `anlart`, `bis`, `erdat`, `loevm`, `sparte`, `spebene`, `tariftyp`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `ablsperr`, `anlage`, `loevm`, `vstelle`

## Join Paths
- `EANL.ANLAGE` → `EANLH.ANLAGE` — Installation → History
- `EANL.VSTELLE` → `EVBS.VSTELLE` — Installation → Premise
- `EANL.EQUNR` → `EQUI.EQUNR` — Installation → Equipment

## Programs Using This Table
- `z_bapi_get_deposit.txt`
- `z_bapi_get_mr_info_by_premise.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_zsr_popup.txt`
- `z_check_meter_type.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `ziscs0014.txt`
- `ziscs0031.txt`
- `ziscs0151.txt`
- `ziscs0315f01.txt`
- `zisdm0015f02.txt`
- `zisdm0020.txt`
- `zisdm0025.txt`
- `zisdm0067.txt`
- `zisdm0135.txt`
- `zisdm0177.txt`
- `zisdm0261.txt`
- `zsdsoc001.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
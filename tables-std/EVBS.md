# `EVBS`

**Description:** Premise — premise/installation location
**Category:** Standard SAP Table
**References:** 317 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/evbs/) — validated 2026-05-30, schema v1.0
**Schema fields:** 20 fields | **Data types:** CHAR(16), DATS(2), LANG(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `HAUS` | HAUS | — | CHAR | 30 | 0 | Connection Object |
| `STR_ERG2` | AD_STRSPP2 | — | CHAR | 40 | 0 | Street 3 |
| `HAUS_NUM2` | AD_HSNM2 | — | CHAR | 10 | 0 | House number supplement |
| `TXTLANGU` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `LGZUSATZ` | LGZUSATZ | — | CHAR | 40 | 0 | Additional Information on Location |
| `VBSART` | VBSART | TE102 | CHAR | 8 | 0 | Type of premise |
| `EIGENT` | E_GPARTNER | BUT000 | CHAR | 10 | 0 | Owner |
| `OBJNR` | J_OBJNR | ONR00 | CHAR | 22 | 0 | Object number |
| `TPLNUMMER` | TPLNUMMER | IFLOT | CHAR | 30 | 0 | Number of functional location |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `ANZPERS` | ANZ_PERS | — | NUMC | 3 | 0 | Number of persons |
| `FLOOR` | AD_FLOOR | — | CHAR | 10 | 0 | Floor in building |
| `ROOMNUMBER` | AD_ROOMNUM | — | CHAR | 10 | 0 | Room or Appartment Number |
| `HPTWHNSITZ` | MAINRESI | — | CHAR | 1 | 0 | Main residence |
| `STR_ERG4` | AD_LCTN | — | CHAR | 40 | 0 | Street 5 |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `EIGENT` | EVBS | MANDT | BUT000 |  | |
| `EIGENT` | EVBS | EIGENT | BUT000 |  | |
| `MANDT` | EVBS | MANDT | T000 |  | |
| `OBJNR` | EVBS | MANDT | ONR00 |  | |
| `OBJNR` | EVBS | OBJNR | ONR00 |  | |
| `TPLNUMMER` | EVBS | MANDT | IFLOT |  | |
| `TPLNUMMER` | EVBS | TPLNUMMER | IFLOT |  | |
| `TXTLANGU` | EVBS | TXTLANGU | T002 |  | |
| `VBSART` | EVBS | MANDT | TE102 |  | |
| `VBSART` | EVBS | VBSART | TE102 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ERDAT`, `HAU`, `HAUS`, `STR_ERG2`, `VSTELLE`, `aedat`, `erdat`, `floor`, `haus`, `haus_num2`, `loevm`, `roomnumber`, `str_erg2`, `str_erg4`, `vbsart`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VSTELLE`, `haus`, `loevm`, `vstelle`

## Join Paths
- `EVBS.HAUS` → `EHAUISU.HAUS` — Premise → Connection Object

## Programs Using This Table
- `z_adms_ccms_call_take.txt`
- `z_adms_ccms_cust_query_1a.txt`
- `z_bapi_get_deposit.txt`
- `z_bapi_simple_accinfo.txt`
- `z_iscs_suppressmovein.txt`
- `z_isdm_get_premise_ext.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0011.txt`
- `ziscs0048.txt`
- `ziscs0068.txt`
- `ziscs0116.txt`
- `ziscs0125.txt`
- `ziscs0150.txt`
- `ziscs0184.txt`
- `ziscs0251.txt`
- `ziscs0368.txt`
- `zisdm0015f02.txt`
- `zisdm0091.txt`
- `zisdm0116.txt`
- `zismd0002.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
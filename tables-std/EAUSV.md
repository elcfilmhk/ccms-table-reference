# `EAUSV`

**Description:** Move-Out Document V — end of supply extended
**Category:** Standard SAP Table
**References:** 47 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eausv/) — validated 2026-05-30, schema v1.0
**Schema fields:** 23 fields | **Data types:** CHAR(18), DATS(5)

## Key Fields
`ANLAGE`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ANLAGE` | ANLAGE | EANL | CHAR | 10 | 0 | Installation |
| `VSTELLE` | VSTELLE | EVBS | CHAR | 10 | 0 | Premise |
| `AUSZDAT` | AUSZDAT | — | DATS | 8 | 0 | Move-Out Date |
| `OHNEEINZ` | OHNEEINZ | EOHNEEINZ | CHAR | 2 | 0 | Move-out w/o move-in |
| `STORAUSZ` | STORAUSZ | — | CHAR | 1 | 0 | Indicator: move-out document was reversed |
| `STORMAHNV` | MAHNV_KK | — | CHAR | 2 | 0 | Dunning Procedure |
| `ABSSTOPKZ` | ABSSTOPKZ | — | CHAR | 1 | 0 | Stop budget billing plan |
| `KZSONDAUSZ` | KZSONDAUSZ | — | CHAR | 1 | 0 | Special move-out processing case exists |
| `AUTEIGEINZ` | AUTEIGEINZ | — | CHAR | 1 | 0 | Automatic Owner Move-In |
| `ABSSTOPDAT` | ABSSTOPANFO | — | DATS | 8 | 0 | Final request date for BB requests for move-in/out |
| `SCHLFAKT` | SCHLFAKT | — | CHAR | 1 | 0 | Joint final billing for move-in/out |
| `MAHNV` | MAHNV_KK | — | CHAR | 2 | 0 | Dunning Procedure |
| `MANSP` | MANSP_KK | — | CHAR | 1 | 0 | Dunning Lock Reason |
| `MAHNVUMZ` | MAHNV_UMZ | — | CHAR | 2 | 0 | Move-in/out dunning procedure |
| `MANOUTSORT` | MANOUTSORT | — | CHAR | 8 | 0 | Reason for manual outsorting in billing |
| `KEINABLBEL` | KEINABLBEL | — | CHAR | 1 | 0 | Do Not Create Card for Meter Reading by Customer |
| `ABRDATS` | ABRDATS | — | DATS | 8 | 0 | Scheduled Billing Date |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ANLAGE` | EAUSVKEY | MANDT | EANL |  | |
| `ANLAGE` | EAUSV | ANLAGE | EANL |  | |
| `AUSZBELEG` | EAUSV | MANDT | EAUS |  | |
| `AUSZBELEG` | EAUSV | AUSZBELEG | EAUS |  | |
| `MANDT` | EAUSV | MANDT | T000 |  | |
| `OHNEEINZ` | EAUSV | MANDT | EOHNEEINZ |  | |
| `OHNEEINZ` | EAUSV | OHNEEINZ | EOHNEEINZ |  | |
| `VERTRAG` | EAUSV | MANDT | EVER |  | |
| `VERTRAG` | EAUSV | VERTRAG | EVER |  | |
| `VSTELLE` | EAUSV | MANDT | EVBS |  | |
| `VSTELLE` | EAUSV | VSTELLE | EVBS |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ANLAGE`, `AUSZBELEG`, `AUSZDAT`, `STORAUSZ`, `VERTRAG`, `VSTELLE`, `aedat`, `aenam`, `anlage`, `auszbeleg`, `auszdat`, `erdat`, `ernam`, `storausz`, `vertrag`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VSTELLE`, `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_crm_isu_contracts.txt`
- `z_iscs_contract_chng_doc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0019.txt`
- `ziscs0028.txt`
- `ziscs0038.txt`
- `ziscs0067.txt`
- `ziscs0184.txt`
- `ziscs0252f01.txt`
- `ziscs0436.txt`
- `ziscs_sms02.txt`
- `zisdm0151f01.txt`
- `zisdm0153f01.txt`
- `zisdm0154.txt`
- `zisdm0190.txt`
- `zisdm_csmp_from_move_out.txt`
- `zisfi0038.txt`
- `zissd00101.txt`
- `zmoveindoc.txt`
- `zmoveinout.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
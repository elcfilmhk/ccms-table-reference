# `EAUS`

**Description:** Move-Out Document — end of supply document
**Category:** Standard SAP Table
**References:** 65 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eaus/) — validated 2026-05-30, schema v1.0
**Schema fields:** 34 fields | **Data types:** CHAR(26), DATS(7), NUMC(1)

## Key Fields
`VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KUNDE` | BU_PARTNER | BUT000 | CHAR | 10 | 0 | Business Partner Number |
| `VKONT` | VKONT_KK | FKKVK | CHAR | 12 | 0 | Contract Account Number |
| `BVAR` | AUSZBVAR | — | CHAR | 4 | 0 | Move-out processing variant |
| `VORLAUSZ` | AUSZBELEG | — | CHAR | 12 | 0 | Consecutive number of move-out document |
| `DEBWECHS` | DEBWECHS | — | CHAR | 2 | 0 | Reason for customer change |
| `DEPARTUREDATE` | EDEPARTUREDATE | — | DATS | 8 | 0 | Actual move-out date |
| `ABSSTOPKZ` | ABSSTOPKZ | — | CHAR | 1 | 0 | Stop budget billing plan |
| `ABSSTOPANFO` | ABSSTOPANFO | — | DATS | 8 | 0 | Final request date for BB requests for move-in/out |
| `SCHLUSSRECH` | SCHLUSSRECH | — | CHAR | 1 | 0 | Automatic final bill requested |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `OPBEL` | OPBEL_KK | — | CHAR | 12 | 0 | Number of Contract Accts Rec. &amp; Payable Doc. |
| `AUTBEST` | AUTBEST | — | CHAR | 1 | 0 | Move-out confirmation created automatically |
| `FORMBEST` | FORMBEST | — | CHAR | 30 | 0 | Application form for move-out confirmation |
| `ANZBEST` | ANZBEST | — | NUMC | 2 | 0 | Number of move-in/out confirmations already created |
| `DELAYED_PRINT` | RF_DELAYED_PRINT | — | CHAR | 1 | 0 | Create Print Request Instead Of Printout |
| `AUSWFORM` | AUSWFORM | — | CHAR | 1 | 0 | Move-Out Confirmation, Form Selection Dialog Requested |
| `AUTSICHWARN` | AUTSICHWARN | — | CHAR | 1 | 0 | Warning for automatic save |
| `BPC_CCLASS` | CT_CCLASS | — | CHAR | 4 | 0 | Contact Class |
| `BPC_ACTIVITY` | CT_ACTIVIT | — | CHAR | 4 | 0 | Contact Action |
| `BPC_ACTIVITY2` | CT_ACTIVIT | — | CHAR | 4 | 0 | Contact Action |
| `GPVKCHDATE` | ECGPVKCHDATE | — | DATS | 8 | 0 | Effective date for changes to BP &amp; CA in move-in/out |
| `FROMMOVEIN` | FROMMOVEIN | — | CHAR | 1 | 0 | Indicator: No move-out notification exists |
| `GPVKREVERSE` | EGPVKREVERSE | — | CHAR | 1 | 0 | Delete Planned Changes to BP and CA During Reversal |
| `STORGPART` | STORGPART | — | CHAR | 1 | 0 | Reverse changes to customer also |
| `STORKTO` | STORKTO | — | CHAR | 1 | 0 | Reverse changes to account also |
| `STORAUSZ` | STORAUSZ | — | CHAR | 1 | 0 | Indicator: move-out document was reversed |
| `SSWTCREASON` | SSWTCREASON | TE960 | CHAR | 2 | 0 | Reasons for contract change |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `KUNDE` | EAUSKEY | MANDT | BUT000 |  | |
| `KUNDE` | EAUS | KUNDE | BUT000 |  | |
| `MANDT` | EAUS | MANDT | T000 |  | |
| `SSWTCREASON` | EAUS | SSWTCREASON | TE960 |  | |
| `SSWTCREASON` | EAUSKEY | MANDT | TE960 |  | |
| `VKONT` | EAUSKEY | MANDT | FKKVK |  | |
| `VKONT` | EAUS | VKONT | FKKVK |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUSZBELEG`, `ERDAT`, `KUNDE`, `STORAUSZ`, `VKONT`, `aedat`, `auszbeleg`, `departuredate`, `erdat`, `kunde`, `loevm`, `storausz`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ERDAT`, `VKONT`, `aedat`, `erdat`, `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_track_mo.txt`
- `z_calculate_deposit.txt`
- `z_get_ca_bp_modoc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0161.txt`
- `ziscs0177.txt`
- `ziscs0184.txt`
- `ziscs0289f.txt`
- `ziscs0436.txt`
- `zisfi0027.txt`
- `zisfi0038.txt`
- `zisfi0039.txt`
- `zisfi0093.txt`
- `zisfi0103.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test.txt`
- `zisfi0116_test3.txt`
- `zisfi0341.txt`
- `zisfiecau01_1.txt`
- `zissd00101.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
# `BUT0ID`

**Description:** BP Identification — ID documents
**Category:** Standard SAP Table
**References:** 74 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/but0id/) — validated 2026-05-30, schema v1.0
**Schema fields:** 8 fields | **Data types:** CHAR(4), DATS(3), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `INSTITUTE` | BU_ID_INSTITUTE | — | CHAR | 40 | 0 | Responsible Institution for ID Number |
| `ENTRY_DATE` | BU_ID_ENTRY_DATE | — | DATS | 8 | 0 | Date of Entry for ID Number |
| `VALID_DATE_FROM` | BU_ID_VALID_DATE_FROM | — | DATS | 8 | 0 | Validity Start for ID Number |
| `VALID_DATE_TO` | BU_ID_VALID_DATE_TO | — | DATS | 8 | 0 | Validity End for ID Number |
| `COUNTRY` | BU_IDCOUNTRY | T005 | CHAR | 3 | 0 | Country in Which ID Number is Valid or Was Assigned |
| `REGION` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `IDNUMBER_GUID` | BU_ID_GUID | — | RAW | 16 | 0 | GUID of a Business Partner Identification Number |
| `BP_EEW_BUT0ID` | DUMMY | — | CHAR | 1 | 0 | Dummy function in length 1 |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `COUNTRY` | SYST | MANDT | T005 |  | |
| `COUNTRY` | BUT0ID | COUNTRY | T005 |  | |
| `PARTNER` | BUT0ID | CLIENT | BUT000 |  | |
| `PARTNER` | BUT0ID | PARTNER | BUT000 |  | |
| `REGION` | BUT0ID | REGION | T005S |  | |
| `REGION` | SYST | MANDT | T005S |  | |
| `REGION` | GT_BUT0ID | COUNTRY | T005S |  | |
| `TYPE` | BUT0ID | CLIENT | TB039A |  | |
| `TYPE` | BUT0ID | TYPE | TB039A |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `idnumber`, `partner`, `type`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `idnumber`, `partner`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_bapi_val_iden.txt`
- `z_bp_id_validation.txt`
- `ziscrm0006f01.txt`
- `ziscrm0008f01.txt`
- `ziscrm0010f01.txt`
- `ziscrm0031f01.txt`
- `ziscs0244.txt`
- `ziscs0285.txt`
- `ziscs0322.txt`
- `ziscs0368.txt`
- `ziscs0802_f01.txt`
- `ziscseec_eec_elig_check.txt`
- `ziscspc_sdu_reg_ben.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscvdatamskdatabackup.txt`
- `zisfi0305_f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
# `EHAUISU`

**Description:** Connection Object — premise connection object
**Category:** Standard SAP Table
**References:** 79 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ehauisu/) — validated 2026-05-30, schema v1.0
**Schema fields:** 5 fields | **Data types:** CHAR(4), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `COUNC` | COUNC | — | CHAR | 3 | 0 | County Code |
| `REGIOGROUP` | REGIOGROUP | — | CHAR | 8 | 0 | Regional structure grouping |
| `REGPOLIT` | REGPOLIT | — | CHAR | 8 | 0 | Political regional structure element |
| `REGIOGROUP_PERM` | REGIOGROUP_PERMIT | — | CHAR | 8 | 0 | Regional structure group for supply permit processing |
| `CRM_GUID` | EHAU_GUID | — | RAW | 16 | 0 | CRM GUID of Connection Object |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `HAUS` | EHAUISU | MANDT | IFLOT |  | |
| `HAUS` | EHAUISU | HAUS | IFLOT |  | |
| `MANDT` | EHAUISU | MANDT | T000 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `HAUS`, `counc`, `haus`, `regiogroup`, `regpolit`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `HAUS`, `haus`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isdm_mol_map_fc_loc.txt`
- `ziscrm0318forms.txt`
- `ziscs0022.txt`
- `ziscs0146.txt`
- `ziscs0184.txt`
- `ziscs0283.txt`
- `zisdm0022_bulk.txt`
- `zisdm0051.txt`
- `zisdm0058.txt`
- `zisdm0084.txt`
- `zisdm0089.txt`
- `zisdm0104.txt`
- `zisdm0105.txt`
- `zisdm0155f01.txt`
- `zisdm0174.txt`
- `zisdm0175.txt`
- `zisdm0242f01.txt`
- `zisdm0253.txt`
- `zisdm0347.txt`
- `zisdm_mru_smp_conn_status.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
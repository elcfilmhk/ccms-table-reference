# `USR21`

**Description:** User Address Key — user-address mapping
**Category:** Standard SAP Table
**References:** 50 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/usr21/) — validated 2026-05-30, schema v1.0
**Schema fields:** 10 fields | **Data types:** CHAR(6), NUMC(1), RAW(3)

## Key Fields
`ADDRNUMBER`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `PERSNUMBER` | AD_PERSNUM | ADRP | CHAR | 10 | 0 | Person number |
| `ADDRNUMBER` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `KOSTL` | XUKOSTL | — | CHAR | 8 | 0 | Cost center |
| `START_MENU` | XUSTART | — | CHAR | 30 | 0 | Start menu |
| `IDADTYPE` | SUIDADTYPE | — | NUMC | 2 | 0 | Address Type of the Identity |
| `BPPERSON` | BU_PARTNER_GUID | — | RAW | 16 | 0 | Business Partner GUID |
| `ORGANIZATION` | BU_PARTNER_GUID | — | RAW | 16 | 0 | Business Partner GUID |
| `RESPONSIBLE` | SUIDRESPONSIBLE | — | CHAR | 12 | 0 | User Responsible for Technical User Account |
| `TECHDESC` | SUIDTECHDESC | — | CHAR | 80 | 0 | Description of the Technical User Account |
| `IDENTITY_GUID` | SUID_GUID | — | RAW | 16 | 0 | GUID of the Identity |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDRNUMBER` | * |  | ADRC |  | |
| `ADDRNUMBER` | USR21 | ADDRNUMBER | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `BNAME` | * |  | USR02 |  | |
| `BNAME` | USR21 | BNAME | USR02 |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | USR21 | PERSNUMBER | ADRP |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADDRNUMBER`, `BNAME`, `MANDT`, `PERSNUMBER`, `addrnumber`, `bname`, `persnumber`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BNAME`, `bname`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_ossnote_436119_adrnum_pernum.txt`
- `zbacbe034.txt`
- `zbacotype.txt`
- `zcazze003.txt`
- `ziscrm0010f01.txt`
- `ziscrm0014.txt`
- `ziscrm0031f01.txt`
- `ziscs0031.txt`
- `ziscs0176.txt`
- `ziscs0176_adj.txt`
- `ziscs0802_f01.txt`
- `ziscs0841.txt`
- `ziscs_rep_log_exec.txt`
- `zisdm0182.txt`
- `zisdm0239f01.txt`
- `zissd00089_f01.txt`
- `zissd00100.txt`
- `zissd00101.txt`
- `zissd00110.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
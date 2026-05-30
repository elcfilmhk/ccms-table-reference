# `ADR6`

**Description:** Email Address — email addresses
**Category:** Standard SAP Table
**References:** 48 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/adr6/) — validated 2026-05-30, schema v1.0
**Schema fields:** 11 fields | **Data types:** CHAR(11)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `FLGDEFAULT` | AD_FLGDFAD | — | CHAR | 1 | 0 | Flag: this address is the default address |
| `FLG_NOUSE` | AD_FLNOUSE | — | CHAR | 1 | 0 | Flag: This Communication Number is Not Used |
| `HOME_FLAG` | AD_FLGHOME | — | CHAR | 1 | 0 | Recipient address in this communication type (mail sys.grp) |
| `SMTP_ADDR` | AD_SMTPADR | — | CHAR | 241 | 0 | E-Mail Address |
| `SMTP_SRCH` | AD_SMTPAD2 | — | CHAR | 20 | 0 | E-Mail Address Search Field |
| `DFT_RECEIV` | AD_DFTRCAD | — | CHAR | 1 | 0 | Flag: Recipient is standard recipient for this address |
| `R3_USER` | AD_R3_USER | — | CHAR | 1 | 0 | Flag: Connected to an SAP System |
| `ENCODE` | AD_ENCODE | — | CHAR | 1 | 0 | Desired Data Coding (E-Mail) |
| `TNEF` | AD_TNEF6 | — | CHAR | 1 | 0 | Flag: Receiver can receive TNEF coding via SMTP |
| `VALID_FROM` | AD_VALFROM | — | CHAR | 14 | 0 | Communication Data: Valid From (YYYYMMDDHHMMSS) |
| `VALID_TO` | AD_VALTO | — | CHAR | 14 | 0 | Communication Data: Valid To (YYYYMMDDHHMMSS) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDRNUMBER` | ADR6 | CLIENT | ADRC |  | |
| `ADDRNUMBER` | ADR6 | ADDRNUMBER | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `CLIENT` | ADR6 | CLIENT | T000 |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | ADR6 | CLIENT | ADRP |  | |
| `PERSNUMBER` | ADR6 | PERSNUMBER | ADRP |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addrnumber`, `consnumber`, `date_from`, `flgdefault`, `persnumber`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `addrnumber`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_wy_lfa1_single_read.txt`
- `zisbi0120.txt`
- `ziscrm0014.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0467.txt`
- `ziscs0807_test_radica_f01.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscv09_f01.txt`
- `zisdm0172.txt`
- `zisdm0356_form.txt`
- `zissd00089_f01.txt`
- `zissd00100.txt`
- `zmmprsi01.txt`
- `zsdbidl01.txt`
- `ztecfaxchg.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
# `ADR2`

**Description:** Phone Number — phone number assignments
**Category:** Standard SAP Table
**References:** 97 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/adr2/) — validated 2026-05-30, schema v1.0
**Schema fields:** 12 fields | **Data types:** CHAR(12)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `COUNTRY` | AD_COMCTRY | T005 | CHAR | 3 | 0 | Country for telephone/fax number |
| `FLGDEFAULT` | AD_FLGDFNR | — | CHAR | 1 | 0 | Standard Sender Address in this Communication Type |
| `FLG_NOUSE` | AD_FLNOUSE | — | CHAR | 1 | 0 | Flag: This Communication Number is Not Used |
| `HOME_FLAG` | AD_FLGHOME | — | CHAR | 1 | 0 | Recipient address in this communication type (mail sys.grp) |
| `TEL_NUMBER` | AD_TLNMBR | — | CHAR | 30 | 0 | Telephone no.: dialling code+number |
| `TEL_EXTENS` | AD_TLXTNS | — | CHAR | 10 | 0 | Telephone no.: Extension |
| `TELNR_LONG` | AD_TELNRLG | — | CHAR | 30 | 0 | Complete number: dialling code+number+extension |
| `TELNR_CALL` | AD_TELNRCL | — | CHAR | 30 | 0 | Telephone number for determining caller |
| `DFT_RECEIV` | AD_FLGSMS | — | CHAR | 1 | 0 | Indicator: Telephone is SMS-Enabled |
| `R3_USER` | AD_FLGMOB | — | CHAR | 1 | 0 | Indicator: Telephone is a Mobile Telephone |
| `VALID_FROM` | AD_VALFROM | — | CHAR | 14 | 0 | Communication Data: Valid From (YYYYMMDDHHMMSS) |
| `VALID_TO` | AD_VALTO | — | CHAR | 14 | 0 | Communication Data: Valid To (YYYYMMDDHHMMSS) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADDRNUMBER` | ADR2 | CLIENT | ADRC |  | |
| `ADDRNUMBER` | ADR2 | ADDRNUMBER | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `ADDRNUMBER` | * |  | ADRC |  | |
| `CLIENT` | ADR2 | CLIENT | T000 |  | |
| `COUNTRY` | ADR2 | CLIENT | T005 |  | |
| `COUNTRY` | ADR2 | COUNTRY | T005 |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | * |  | ADRP |  | |
| `PERSNUMBER` | ADR2 | CLIENT | ADRP |  | |
| `PERSNUMBER` | ADR2 | PERSNUMBER | ADRP |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addrnumber`, `consnumber`, `date_from`, `persnumber`, `r3_user`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `addrnumber`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_bapi_bp_details.txt`
- `z_update_crm_bp.txt`
- `zadru_create.txt`
- `ziscs0031.txt`
- `ziscs0238.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0368.txt`
- `ziscs_sms02.txt`
- `ziscseec_comm_frmwrk_dr.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscv09_f01.txt`
- `zisdm0313_adr.txt`
- `zisfi0214.txt`
- `zisfi0250.txt`
- `zisfi0250_backup.txt`
- `zisfi0250_backup_1.txt`
- `zissd00111.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
# `DPAYP`

**Description:** Direct Debit Line — DD payment line item
**Category:** Standard SAP Table
**References:** 13 SELECT statements across 10 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dpayp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 49 fields | **Data types:** CHAR(35), CUKY(1), CURR(7), DATS(3), DEC(1), NUMC(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `GPA2T` | GPA2T_PAY | — | CHAR | 2 | 0 | Category of business partner making a payment |
| `GPA2R` | GPA2R_PAY | — | CHAR | 12 | 0 | Reference to Business Partner Giving Payment Instruction |
| `ACC1T` | ACC1T_PAY | — | CHAR | 2 | 0 | Contract Account Category |
| `ACC1R` | ACC1R_PAY | — | CHAR | 18 | 0 | Reference to Contract Account |
| `VOR1T` | VOR1T_PAY | — | CHAR | 2 | 0 | Activity type |
| `VOR1R` | VOR1R_PAY | — | CHAR | 4 | 0 | Reference to Main Transaction |
| `VOR2T` | VOR1T_PAY | — | CHAR | 2 | 0 | Activity type |
| `VOR2R` | VOR2R_PAY | — | CHAR | 4 | 0 | Reference to Subtransaction |
| `TXT1T` | TXT1T_PAY | — | CHAR | 2 | 0 | Long text type |
| `TXT1R` | TXT1R_PAY | — | CHAR | 30 | 0 | Long text reference |
| `ADRNR` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `NAME1` | AD_NAME1 | — | CHAR | 40 | 0 | Name 1 |
| `LAND1` | LAND1 | T005 | CHAR | 3 | 0 | Country Key |
| `REGIO` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `ORT01` | AD_CITY1 | — | CHAR | 40 | 0 | City |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `FAEDT` | FAEDT_F110 | — | DATS | 8 | 0 | Due Date of Payment |
| `SKTPA` | SKTPA_KK | — | DEC | 5 | 3 | Accepted cash discount rate |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `BETRW` | BETRW_KK | — | CURR | 13 | 2 | Amount in Transaction Currency with +/- Sign |
| `AUGBH` | AUGBH_KK | — | CURR | 13 | 2 | Clearing amount in local currency with +/- sign |
| `AUGBW` | AUGBW_KK | — | CURR | 13 | 2 | Clearing Amount in Transaction Currency (With +/- Sign) |
| `ASKTH` | ASKTH_KK | — | CURR | 13 | 2 | Proportional cash discount in local currency |
| `ASKTW` | ASKTW_KK | — | CURR | 13 | 2 | Proportional cash discount in transaction currency |
| `POKEN` | POKEN_PAY | TFKPK | NUMC | 3 | 0 | Item indicator in payment program |
| `ZLSPR` | SPZAH_KK | TFK008 | CHAR | 1 | 0 | Lock Reason for Automatic Payment |
| `CLRLO` | CLRLO_KK | TFK004B | CHAR | 1 | 0 | Clearing Lock Reason |
| `BUKRS` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | — | CHAR | 4 | 0 | Business Area |
| `C4EYE` | C4EYE_KK | — | CHAR | 2 | 0 | Check Reason for Workflows Acc. to Dual Control Principle |
| `OPTXT` | SGTXT | — | CHAR | 50 | 0 | Item Text |
| `REF1T` | REFIT_PAY | — | CHAR | 2 | 0 | Reference information type |
| `REF1R` | REFIN_PAY | — | CHAR | 40 | 0 | Reference information |
| `REF2T` | REFIT_PAY | — | CHAR | 2 | 0 | Reference information type |
| `REF2R` | REFIN_PAY | — | CHAR | 40 | 0 | Reference information |
| `REF3T` | REFIT_PAY | — | CHAR | 2 | 0 | Reference information type |
| `REF3R` | REFIN_PAY | — | CHAR | 40 | 0 | Reference information |
| `VTREF` | VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `VTPOS` | VTPOS_KK | — | NUMC | 6 | 0 | Contract: Item Number |
| `VTRE2` | VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `LZBKZ` | LZBKZ | T015L | CHAR | 3 | 0 | State Central Bank Indicator |
| `LANDL` | LANDL | T005 | CHAR | 3 | 0 | Supplying Country |
| `STCD1` | STCD1 | — | CHAR | 16 | 0 | Tax Number 1 |
| `AQSBW` | AQSBW_KK | — | CURR | 13 | 2 | Proportional Withholding Tax Amount In Transaction Currency |
| `AQSBH` | AQSBH_KK | — | CURR | 13 | 2 | Proportional Withholding Tax Amount In Local Currency |
| `QSSKZ` | QSSKZ | — | CHAR | 2 | 0 | Withholding Tax Code |
| `STAKZ` | STAKZ_KK | — | CHAR | 1 | 0 | Type of statistical item |
| `SUBAP` | SUBAP_KK | — | CHAR | 1 | 0 | Subapplication in Contract Accounts Receivable and Payable |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADRNR` | DPAYP | MANDT | ADRC |  | |
| `ADRNR` | DPAYP | ADRNR | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `CLRLO` | DPAYP | MANDT | TFK004B |  | |
| `CLRLO` | DPAYP | CLRLO | TFK004B |  | |
| `LAND1` | DPAYP | LAND1 | T005 |  | |
| `LAND1` | SYST | MANDT | T005 |  | |
| `LANDL` | SYST | MANDT | T005 |  | |
| `LANDL` | DPAYP | LANDL | T005 |  | |
| `LZBKZ` | SYST | MANDT | T015L |  | |
| `LZBKZ` | DPAYP | LZBKZ | T015L |  | |
| `MANDT` | DPAYP | MANDT | T000 |  | |
| `POKEN` | DPAYP | POKEN | TFKPK |  | |
| `REGIO` | DPAYP | REGIO | T005S |  | |
| `REGIO` | SYST | MANDT | T005S |  | |
| `REGIO` | DPAYP | LAND1 | T005S |  | |
| `WAERS` | DPAYP | MANDT | TCURC |  | |
| `WAERS` | DPAYP | WAERS | TCURC |  | |
| `ZLSPR` | DPAYP | MANDT | TFK008 |  | |
| `ZLSPR` | DPAYP | ZLSPR | TFK008 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_paymedium_cheque_refund.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zbacbt600.txt`
- `ziscs_migration_adjustment_m4.txt`
- `zisfi0028.txt`
- `zisfi0081.txt`
- `zisfi0099.txt`
- `zisfi0204.txt`
- `zisfi0238.txt`
- `zisfi0240.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
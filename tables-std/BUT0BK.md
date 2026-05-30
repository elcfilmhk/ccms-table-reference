# `BUT0BK`

**Description:** BP Bank Details — bank account info
**Category:** Standard SAP Table
**References:** 71 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/but0bk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 19 fields | **Data types:** CHAR(15), DEC(3), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BANKS` | BU_BANKS | T005 | CHAR | 3 | 0 | Bank Country Key |
| `BANKL` | BU_BANKK | — | CHAR | 15 | 0 | Bank Key |
| `BANKN` | BU_BANKN | — | CHAR | 18 | 0 | Bank Account Number |
| `BKONT` | BU_BKONT | — | CHAR | 2 | 0 | Bank Control Key |
| `BKREF` | BU_BKREF | — | CHAR | 20 | 0 | Reference Details for Bank Details |
| `KOINH` | BU_KOINH | — | CHAR | 60 | 0 | Account Holder Name |
| `BKEXT` | BU_BKEXT | — | CHAR | 20 | 0 | Bank details ID in external system |
| `XEZER` | BU_XEZER | — | CHAR | 1 | 0 | Indicator: Collection Authorization |
| `ACCNAME` | BU_BANKACCNAME | — | CHAR | 40 | 0 | Name of Bank Account |
| `MOVE_BKVID` | BU_MOVE_BKVID | — | CHAR | 4 | 0 | ID of Target Details for Change of Bank Details (BP) |
| `BK_VALID_FROM` | BU_BK_VALID_FROM | — | DEC | 15 | 0 | Validity Start of Business Partner Bank Details |
| `BK_VALID_TO` | BU_BK_VALID_TO | — | DEC | 15 | 0 | Validity End of Business Partner Bank Details |
| `BK_MOVE_DATE` | BU_BK_MOVE_DATE | — | DEC | 15 | 0 | Date of Change to Bank Details (BP) |
| `IBAN` | BU_IBAN | — | CHAR | 34 | 0 | IBAN (International Bank Account Number) |
| `BANK_GUID` | BU_BANK_GUID | — | RAW | 16 | 0 | Bank GUID |
| `ACCOUNT_ID` | BU_ACCOUNT_ID | — | CHAR | 35 | 0 | Bank Account Number (New) |
| `CHECK_DIGIT` | BU_ACCOUNT_CHECK | — | CHAR | 2 | 0 | Bank Account Check Digit |
| `ACCOUNT_TYPE` | BU_ACCOUNT_TYPE | — | CHAR | 3 | 0 | Bank Account Type |
| `BP_EEW_BUT0BK` | DUMMY | — | CHAR | 1 | 0 | Dummy function in length 1 |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BANKS` | BUT0BK | MANDT | T005 |  | |
| `BANKS` | BUT0BK | BANKS | T005 |  | |
| `MANDT` | BUT0BK | MANDT | T000 |  | |
| `PARTNER` | BUT0BK | MANDT | BUT000 |  | |
| `PARTNER` | BUT0BK | PARTNER | BUT000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_bank_details.txt`
- `z_bapi_bank_details_noname.txt`
- `z_bapi_get_ap_status.txt`
- `z_bapi_get_track_mo.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_check_ca_ebill_autopay.txt`
- `z_get_bank_name.txt`
- `z_paymedium_eft_30.txt`
- `ziscs0184.txt`
- `ziscs0802_f01.txt`
- `ziscs0815forms.txt`
- `ziscs0817forms.txt`
- `ziscspc_sdu_ben_view.txt`
- `ziscspc_sdu_reg_ben.txt`
- `ziscv03.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscvdatamskdatabackup.txt`
- `zisfi0219.txt`
- `zvkk_acct_mgr_bp_dchck.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
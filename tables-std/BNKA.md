# `BNKA`

**Description:** Bank Master — bank details
**Category:** Standard SAP Table
**References:** 19 SELECT statements across 18 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BANKL` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BANKA`, `BANKL`, `BANKS`, `bankl`, `banks`, `loevm`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BANKL`, `loevm`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_get_bank_name.txt`
- `ziscs0500.txt`
- `ziscs0800f01.txt`
- `ziscs0800i01.txt`
- `ziscs0802_f01.txt`
- `ziscs0815forms.txt`
- `ziscs0817forms.txt`
- `ziscsbnka_f01.txt`
- `zisfi0039.txt`
- `zisfi0051.txt`
- `zisfi0125.txt`
- `zisfi0157.txt`
- `zisfi0277f01.txt`
- `zisfi0337_f01.txt`
- `zisfi_data_conversion_f01.txt`
- `zisfi_ddconversion_file_f01.txt`
- `ztest_mzcs380f01.txt`
- `ztest_zisfi0277f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_

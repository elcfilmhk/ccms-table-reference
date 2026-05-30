# `BNKA`

**Description:** Bank Master — bank details
**Category:** Standard SAP Table
**References:** 19 SELECT statements across 18 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bnka/) — validated 2026-05-30, schema v1.0
**Schema fields:** 18 fields | **Data types:** CHAR(17), DATS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ERDAT` | ERDAT_BF | — | DATS | 8 | 0 | Date on which the record was created |
| `ERNAM` | ERNAM_BF | — | CHAR | 12 | 0 | Name of person who created the object |
| `BANKA` | BANKA | — | CHAR | 60 | 0 | Name of bank |
| `PROVZ` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `STRAS` | STRAS_GP | — | CHAR | 35 | 0 | House number and street |
| `ORT01` | ORT01_GP | — | CHAR | 35 | 0 | City |
| `SWIFT` | SWIFT | — | CHAR | 11 | 0 | SWIFT/BIC for International Payments |
| `BGRUP` | BGRUP | — | CHAR | 2 | 0 | Bank group (bank network) |
| `XPGRO` | XPGRO | — | CHAR | 1 | 0 | Post Office Bank Current Account |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `BNKLZ` | BANKL | — | CHAR | 15 | 0 | Bank number |
| `PSKTO` | PSKTO_CH | — | CHAR | 16 | 0 | Post office bank current account number |
| `ADRNR` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `BRNCH` | BRNCH | — | CHAR | 40 | 0 | Bank Branch |
| `CHKME` | CHECKMETH | — | CHAR | 4 | 0 | Check digit calculation method |
| `VERS` | VERS_BF | — | CHAR | 3 | 0 | Format of File with Bank Data |
| `BICKY` | PRQ_BICKY | — | CHAR | 12 | 0 | Key of a BIC+ data record (Swift) |
| `RCCODE` | PRQ_RCC | — | CHAR | 15 | 0 | Routing control code |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BANKS` | BNKA | MANDT | T005 |  | |
| `BANKS` | BNKA | BANKS | T005 |  | |
| `MANDT` | BNKA | MANDT | T000 |  | |
| `PROVZ` | BNKA | MANDT | T005S |  | |
| `PROVZ` | BNKA | BANKS | T005S |  | |
| `PROVZ` | BNKA | PROVZ | T005S |  | |

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
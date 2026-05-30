# `USR02`

**Description:** User Master — user logon data
**Category:** Standard SAP Table
**References:** 47 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/usr02/) — validated 2026-05-30, schema v1.0
**Schema fields:** 42 fields | **Data types:** CHAR(15), DATS(13), INT1(6), RAW(7), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BCODE` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `GLTGV` | XUGLTGV | — | DATS | 8 | 0 | User valid from |
| `GLTGB` | XUGLTGB | — | DATS | 8 | 0 | User valid to |
| `USTYP` | XUUSTYP | — | CHAR | 1 | 0 | User Type |
| `CLASS` | XUCLASS | USGRP | CHAR | 12 | 0 | User group in user master maintenance |
| `LOCNT` | XULOCNT | — | INT1 | 3 | 0 | Number of failed logon attempts |
| `UFLAG` | XUUFLAG | — | INT1 | 3 | 0 | User Lock Status |
| `ACCNT` | XUACCNT | — | CHAR | 12 | 0 | Account ID |
| `ANAME` | XUANAME | — | CHAR | 12 | 0 | Creator of the User Master Record |
| `ERDAT` | XUERDAT | — | DATS | 8 | 0 | Creation Date of the User Master Record |
| `TRDAT` | XULDATE | — | DATS | 8 | 0 | Last Logon Date |
| `LTIME` | XULTIME | — | TIMS | 6 | 0 | Last Logon Time |
| `OCOD1` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `BCDA1` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `CODV1` | XUCODEVERS | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (Old Systems) |
| `OCOD2` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `BCDA2` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `CODV2` | XUCODEVERS | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (Old Systems) |
| `OCOD3` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `BCDA3` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `CODV3` | XUCODEVERS | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (Old Systems) |
| `OCOD4` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `BCDA4` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `CODV4` | XUCODEVERS | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (Old Systems) |
| `OCOD5` | XUCODE | — | RAW | 8 | 0 | Password Hash Key |
| `BCDA5` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `CODV5` | XUCODEVERS | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (Old Systems) |
| `VERSN` | XUVERSION | — | CHAR | 3 | 0 | User master record version |
| `CODVN` | XUCODEVER2 | — | CHAR | 1 | 0 | Code Version of Password Hash Algorithm (New Systems) |
| `TZONE` | TZNZONE | TTZZ | CHAR | 6 | 0 | Time Zone |
| `ZBVMASTER` | XUZBVFLAG | — | CHAR | 1 | 0 | CUA User Template: Logon Not Possible Here |
| `PASSCODE` | PWD_SHA1 | — | RAW | 20 | 0 | Password Hash Value (SHA1, 160 Bit) |
| `PWDCHGDATE` | XUBCDAT | — | DATS | 8 | 0 | Date of Last Password Change |
| `PWDSTATE` | PWDCHGSTATE | — | INT1 | 3 | 0 | Password Change: Required / Allowed / Not Possible |
| `RESERVED` | XUCUACNTL | — | INT1 | 3 | 0 | CUA Control Information |
| `PWDHISTORY` | XUPWDHIST | — | INT1 | 3 | 0 | Indicator: Password History Stored in Table USRPWDHISTORY |
| `PWDLGNDATE` | XULPDAT | — | DATS | 8 | 0 | Date of Last Password Logon |
| `PWDSETDATE` | XUSPDAT | — | DATS | 8 | 0 | Date: Password Reset by Administrator |
| `PWDINITIAL` | XUPWDINIT | — | INT1 | 3 | 0 | Indicator: Password Is Initial (= Set by Administrator) |
| `PWDLOCKDATE` | XUPLDAT | — | DATS | 8 | 0 | Date: Setting of Password Lock |
| `PWDSALTEDHASH` | PWD_HASH_STRING | — | CHAR | 255 | 0 | Password Hash Value (Various Algorithms and Codings) |
| `SECURITY_POLICY` | SECURITY_POLICY_NAME | SEC_POLICY_CUST | CHAR | 40 | 0 | Security Policy Name |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CLASS` | USR02 | MANDT | USGRP |  | |
| `CLASS` | USR02 | CLASS | USGRP |  | |
| `SECURITY_POLICY` | USR02 | MANDT | SEC_POLICY_CUST |  | |
| `SECURITY_POLICY` | USR02 | SECURITY_POLICY | SEC_POLICY_CUST |  | |
| `TZONE` | USR02 | MANDT | TTZZ |  | |
| `TZONE` | USR02 | TZONE | TTZZ |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ANAME`, `BCDA1`, `BCODE`, `BNAME`, `CLASS`, `CODVN`, `ERDAT`, `GLTGB`, `GLTGV`, `LOCNT`, `LTIME`, `MANDT`, `PASSCODE`, `TRDAT`, `UFLAG`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_abap_developer_info.txt`
- `z_zcsh_pid_maint2.txt`
- `zbacbe001.txt`
- `zbacbe004.txt`
- `zbacbe033.txt`
- `zbacbe034.txt`
- `zbacbe036.txt`
- `zbacbe042.txt`
- `zbacbe045.txt`
- `zbacbe060.txt`
- `zbacbe061.txt`
- `zbacbe063.txt`
- `zbacbe087.txt`
- `ziscrm_upd_zcont_acc.txt`
- `ziscs0156.txt`
- `ziscspc_sdu_ben_view.txt`
- `zisfi0166.txt`
- `zissd00101.txt`
- `zmmpre030s.txt`
- `zslaw_plugin.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
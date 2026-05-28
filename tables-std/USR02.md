# `USR02`

**Description:** User Master — user logon data
**Category:** Standard SAP Table
**References:** 47 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BNAME` | | 🔑 | Primary key |

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

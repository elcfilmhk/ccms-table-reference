# ZBAICAUTH
**Description:** Interface Control - Authorization
**Total Fields:** 29
**Key Fields:** MANDT, SYSID, REPID, FUNCT, AUTH

## Programs Using This Table
- `zbaicr001`
- `zbaicri03`
- `zbaicri04`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 4 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 5 | `AUTH` | CHAR | 10 | 🔑 | Authorization Object |
| 6 | `ACTIVE` | CHAR | 1 |  | Interface control- active indicator |
| 7 | `AUTH_FLD1` | CHAR | 12 |  | Authorization name in user master maintenance |
| 8 | `CREATE_DT` | DATS | 8 |  | Interface control - date |
| 9 | `CHANGE_DT` | DATS | 8 |  | Interface control - date |
| 10 | `ZVIEW` | CHAR | 1 |  | Inteface control - view indicator |
| 11 | `AUTH_VAL1` | CHAR | 40 |  | Intreface control - authrorization value |
| 12 | `AUTH_FLD2` | CHAR | 12 |  | Authorization name in user master maintenance |
| 13 | `AUTH_VAL2` | CHAR | 40 |  | Intreface control - authrorization value |
| 14 | `AUTH_FLD3` | CHAR | 12 |  | Authorization name in user master maintenance |
| 15 | `AUTH_VAL3` | CHAR | 40 |  | Intreface control - authrorization value |
| 16 | `AUTH_FLD4` | CHAR | 12 |  | Authorization name in user master maintenance |
| 17 | `AUTH_VAL4` | CHAR | 40 |  | Intreface control - authrorization value |
| 18 | `AUTH_FLD5` | CHAR | 12 |  | Authorization name in user master maintenance |
| 19 | `AUTH_VAL5` | CHAR | 40 |  | Intreface control - authrorization value |
| 20 | `AUTH_FLD6` | CHAR | 12 |  | Authorization name in user master maintenance |
| 21 | `AUTH_VAL6` | CHAR | 40 |  | Intreface control - authrorization value |
| 22 | `AUTH_FLD7` | CHAR | 12 |  | Authorization name in user master maintenance |
| 23 | `AUTH_VAL7` | CHAR | 40 |  | Intreface control - authrorization value |
| 24 | `AUTH_FLD8` | CHAR | 12 |  | Authorization name in user master maintenance |
| 25 | `AUTH_VAL8` | CHAR | 40 |  | Intreface control - authrorization value |
| 26 | `AUTH_FLD9` | CHAR | 12 |  | Authorization name in user master maintenance |
| 27 | `AUTH_VAL9` | CHAR | 40 |  | Intreface control - authrorization value |
| 28 | `AUTH_FLD10` | CHAR | 12 |  | Authorization name in user master maintenance |
| 29 | `AUTH_VAL10` | CHAR | 40 |  | Intreface control - authrorization value |

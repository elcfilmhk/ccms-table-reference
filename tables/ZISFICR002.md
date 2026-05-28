# ZISFICR002
**Description:** Account Class/Account Determination ID Mapping
**Total Fields:** 4
**Key Fields:** MANDT, CLASS

## Programs Using This Table
- `ziscs0256`
- `ziscs0279`
- `ziscs0297`
- `zisfi0347`
- `zisfixacl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CLASS` | CHAR | 4 | 🔑 | Account Class |
| 3 | `CLASSTEXT` | CHAR | 50 |  | Account Class Description |
| 4 | `DETER_ID` | CHAR | 2 |  | Account Determination ID |
